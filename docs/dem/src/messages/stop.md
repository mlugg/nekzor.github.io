# Stop

This message indicates the end of the demo file. The remaining bytes that come after the type byte might not even include the message tick as seen in older engine versions. These bytes can also appear for alignment reasons.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| RemainingData | byte[] | - | - | Optional |
