# NetTick

Part of [NET/SVC](../netsvc.md) message.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| Tick | integer | 4 | 32 | - |
| HostFrameTime¹ | integer | 2 | 16 | - |
| HostFrameTimeStdDeviation¹ | integer | 2 | 16 | - |

¹ Value is scaled up by a factor of 10<sup title="undefined">5</sup> (NET_TICK_SCALEUP).

## Pseudocode Example

```rust,noplaypen,ignore
let tick = read_le_32();
let host_frame_time = read_le_16() / 1e5;
let host_frame_time_std_deviation = read_le_16() / 1e5;
```
