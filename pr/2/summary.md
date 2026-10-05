<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/2/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 15 | +1435 / −54 | 64 / 60 / 0 | 330 / 41 | 85% (77/91) |

⚠️ **14 changed functions not reached by any test:** `MPTDatabase.commit`, `MPTDatabase.Commit`, `BlockChain.GetLogs`, `Database.Cap`, `Database.AddLayer`, `chainWriter.canonicalHash`, `Database.Add`, `Database.add`, …

<details><summary>Largest changed functions (91 in code, 21 in tests)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟢 `chainWriter.queueHead` | `core/blockchain_writer.go:247` | +55 −0 | ✅ |
| 🟢 `MPTDatabase.commit` | `core/state/database_mpt.go:148` | +44 −0 | ⚠️ none |
| 🟡 `MPTDatabase.Commit` | `core/state/database_mpt.go:143` | +1 −37 | ⚠️ none |
| 🟢 `chainWriter.queue` | `core/blockchain_writer.go:207` | +38 −0 | ✅ |
| 🟡 `BlockChain.SetCanonical` | `core/blockchain.go:2977` | +5 −26 | ✅ |
| 🟢 `BlockChain.sendHeadEvents` | `core/blockchain.go:3012` | +26 −0 | ✅ |
| 🟢 `chainWriter.waitJob` | `core/blockchain_writer.go:531` | +25 −0 | ✅ |
| 🟢 `chainWriter.stateLoop` | `core/blockchain_writer.go:346` | +24 −0 | ✅ |
| 🟡 `BlockChain.writeHeadBlock` | `core/blockchain.go:1377` | +2 −20 | ✅ |
| 🟡 `BlockChain.ProcessBlock` | `core/blockchain.go:2371` | +19 −2 | ✅ |

</details>
