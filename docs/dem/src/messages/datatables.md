# DataTables

This message only appears once at the beginning of a demo. It contains network data which the engine used for simulation.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| Size | int | 4 | 32 | - |
| Data | byte[] | Size | Size*8 | [SendTable[]](../classes/sendtable.md)<br>[ServerClassInfo[]](../classes/serverclassinfo.md) |

## Pseudocode Example

```rust,noplaypen,ignore
while read_one_bit() {
    read_send_table();
}

let classes = read_le_i16();

for _ in 0..classes {
    read_server_class_info();
}
```
