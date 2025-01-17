# SvcServerInfo

Part of [NET/SVC](../netsvc.md) message.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| Protocol | int | 1 | 8 | - |
| ServerCount | int | 4 | 32 | - |
| IsHltv | boolean | 0.125 | 1 | - |
| IsDedicated | boolean | 0.125 | 1 | - |
| ClientCrc | int | 4 | 32 | - |
| MaxClasses | int | 2 | 16 | - |
| MapCrc | int | 4 | 32 | - |
| PlayerSlot | int | 1 | 8 | - |
| MaxClients | int | 1 | 8 | - |
| Unk<sup title="New Engine">NE</sup> | int | 4 | 32 | - |
| Unk<sup title="Old Engine">OE</sup> | int | 12 | 96 | - |
| TickInterval | float | 4 | 32 | - |
| COs | char | 1 | 8 | - |
| GameDir | string | - | - | - |
| MapName | string | - | - | - |
| SkyName | string | - | - | - |
| HostName | string | - | - | - |

## Pseudocode Example

```rust,noplaypen,ignore
let protocol = read_le_u16();
let server_count = read_le_u32();
let is_hltv = read_one_bit();
let is_dedicated = read_one_bit();
let client_crc = read_le_u32();
let max_classes = read_le_u16();
let map_crc = read_le_u32();
let player_slot = read_le_u8();
let max_clients = read_le_u8();

let unk = if demo_protocol_3_or_4() {
    read_le_u32()
} else if demo_network_protocol == 24 {
    read_bits(96)
};

let tick_interval = read_le_f32();
let c_os = read_le_u8() as char;
let game_dir = read_ascii_string();
let map_name = read_ascii_string();
let sky_name = read_ascii_string();
let host_name = read_ascii_string();
```
