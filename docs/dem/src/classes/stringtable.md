# SingTable

Part of [StringTables](../messages/stringtables.md) message.

| Name | Type | Size in bytes | Size in bits | Value |
| --- | --- | --- | --- | --- |
| NumOfTables | int | 1 | 8 | - |
| TableName | string | - | - | - |
| NumOfEntries | short | 2 | 16 | - |
| EntryName | string | - | - | - |
| EntrySize | short | 2 | 16 | Optional¹ |
| EntryData | byte[] | EntrySize | EntrySize*8 | Optional |
| NumOfClientEntries | short | 2 | 16 | Optional |
| ClientEntryName | string | - | - | Optional |
| ClientEntrySize | short | 2 | 16 | Optional |
| ClientEntryData | byte[] | ClientEntrySize | ClientEntrySize*8 | Optional |

¹ Optional means to only read the field if the bit before was set.
