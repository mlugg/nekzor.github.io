# UserCmdInfo

Part of [UserCmd](../messages/usercmd.md) message.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| CommandNumber | int | 4 | 32 | Optional¹ |
| TickCount | int | 4 | 32 | Optional |
| ViewAnglesX | float | 4 | 32 | Optional |
| ViewAnglesY | float | 4 | 32 | Optional |
| ViewAnglesZ | float | 4 | 32 | Optional |
| ForwardMove | float | 4 | 32 | Optional |
| SideMove | float | 4 | 32 | Optional |
| UpMove | float | 4 | 32 | Optional |
| Buttons | int | 4 | 32 | Optional |
| Impulse | byte | 1 | 8 | Optional |
| WeaponSelect | int | 1.375 | 11 | Optional |
| WeaponSubtype² | int | 0.75 | 6 | Optional |
| MouseDx | short | 2 | 16 | Optional |
| MouseDy | short | 2 | 16 | Optional |

¹ Optional means to only read the field if the bit before was set.

² This field depends if `WeaponSelect` was set.

## Pseudocode Example

```rust,noplaypen,ignore
if read_one_bit() {
    command_number = read_le_u32();
}

...

if read_one_bit() {
    weapon_select = read_bits(11);

    if read_one_bit() {
        weapon_subtype = read_bits(6);
    }
}

...
```
