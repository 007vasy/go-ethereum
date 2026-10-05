<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/2/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 15 | +1435 / −54 | 64 / 60 / 0 | 330 / 41 | 85% (77/91) |

<details><summary>Largest changed functions (112 total)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟢 `TestAddCap` | `triedb/pathdb/database_test.go:892` | +61 −0 | — |
| 🟢 `testDeferredWriteServesQueuedBlock` | `core/blockchain_writer_test.go:250` | +58 −0 | — |
| 🟢 `chainWriter.queueHead` | `core/blockchain_writer.go:247` | +55 −0 | ✅ |
| 🟢 `MPTDatabase.commit` | `core/state/database_mpt.go:148` | +44 −0 | ⚠️ none |
| 🟡 `MPTDatabase.Commit` | `core/state/database_mpt.go:143` | +1 −37 | ⚠️ none |
| 🟢 `chainWriter.queue` | `core/blockchain_writer.go:207` | +38 −0 | ✅ |
| 🟢 `checkBlockReadable` | `core/blockchain_writer_test.go:173` | +38 −0 | — |
| 🟢 `TestDeferredWriteStopDrains` | `core/blockchain_writer_test.go:363` | +32 −0 | — |
| 🟡 `BlockChain.SetCanonical` | `core/blockchain.go:2977` | +5 −26 | ✅ |
| 🟢 `checkHeadReadable` | `core/blockchain_writer_test.go:213` | +27 −0 | — |

</details>
