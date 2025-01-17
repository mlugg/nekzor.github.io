# SvcBspDecal

Part of [NET/SVC](../netsvc.md) message.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| Pos | float?[] | 0.375 to 8.625 | 3 to 69 | VectorCoord |
| DecalTextureIndex | int | 1.125 | 9 | - |
| EntityIndex¹ | int | 1.125 | 11 | Optional |
| ModelIndex² | int | 1.125 | 11 | - |
| LowPriority | boolean | 0.125 | 8 | - |

¹ Optional means to only read the field if the bit before was set.

² This field depends on `EntityIndex`.

## Pseudocode Example

```rust,noplaypen,ignore
fn read_vector_coords() -> (Optional<f32>, Optional<f32>, Optional<f32>) {
    fn read_vector_coord() -> f32 {
        const COORD_INTEGER_BITS: u8 = 14;
        const COORD_FRACTIONAL_BITS: u8 = 5;
        const COORD_DENOMINATOR: u8 = 1u8 << COORD_FRACTIONAL_BITS;
        const COORD_RESOLUTION: f32 = 1f32 / (COORD_DENOMINATOR as f32);

        let value = 0f32;
        let integer = read_bits(1);
        let fraction = read_bits(1);

        if integer != 0 || fraction != 0 {
            const sign = read_bits(1);
            if integer != 0 {
                integer = read_bits(COORD_INTEGER_BITS) + 1;
            }

            if fraction != 0 {
                fraction = read_bits(COORD_FRACTIONAL_BITS);
            }

            value = integer + fraction * COORD_RESOLUTION;
            if (sign {
                value = -value;
            }
        }

        value
    }

    let (x, y, z) = (read_one_bit(), read_one_bit(), read_one_bit());

    (
         if x != 0 { Some(read_vector_coord()) } else { None },
         if y != 0 { Some(read_vector_coord()) } else { None },
         if z != 0 { Some(read_vector_coord()) } else { None },
    )
}

let pos = read_vector_coords();
let decal_texture_index = read_bits(9);

if read_one_bit() {
    let entity_index = read_bits(11);
    let model_index = read_bits(11);
}

let low_priority = read_one_bit();
```
