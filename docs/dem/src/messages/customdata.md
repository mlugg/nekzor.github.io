# CustomData

This message is used to embed data in a generic way without introducing breaking changes in the demo file format. It is up to the engine whether to use or process this kind of message.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| Unknown | int | 4 | 32 | - |
| Size | int | 4 | 32 | - |
| Data | byte[] | Size | Size*8 | - |
