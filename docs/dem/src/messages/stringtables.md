# StringTables

This message only appears once at the beginning of a demo. It contains network data which the engine used for simulation.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| Size | int | 4 | 32 | - |
| Data | byte[] | Size | Size*8 | [StringTable[]](../classes/stringtable.md) |

## Pseudocode Example

```rust,noplaypen,ignore
let tables = read_le_i8();

for _ in 0..tables {
    read_string_table();
}
```
