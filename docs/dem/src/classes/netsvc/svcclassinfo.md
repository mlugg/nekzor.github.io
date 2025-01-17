# SvcClassInfo

Part of [NET/SVC](../netsvc.md) message.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| Length | integer | 2 | 16 | - |
| CreateOnClient | boolean | 0.125 | 1 | - |
| ServerClasses¹ | byte[] | - | - | ServerClass[] |

¹ Depends if the `CreateOnClient` bit was set.

## Pseudocode Example

```rust,noplaypen,ignore
let length = read_le_i16();
let create_on_client = read_one_bit();

if create_on_client {
    for _ 0..length {
        let class_id = read_bits(length.log2() + 1);
        let class_name = read_ascii_string();
        let data_table_name = read_ascii_string();
    }
}
```
