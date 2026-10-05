<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/3/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 6 | +341 / −17 | 7 / 15 / 0 | 47 / 0 | 29% (2/7) |

⚠️ **5 changed functions not reached by any test:** `FilterMaps.init`, `FilterMaps.tryUnindexTail`, `FilterMaps.indexerLoop`, `FilterMaps.exportCheckpoints`, `FilterMaps.needTailEpoch`

<details><summary>Largest changed functions (7 in code, 10 in tests)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟡 `FilterMaps.init` | `core/filtermaps/filtermaps.go:378` | +29 −8 | ⚠️ none |
| 🟡 `FilterMaps.tryUnindexTail` | `core/filtermaps/indexer.go:361` | +5 −0 | ⚠️ none |
| 🟡 `FilterMaps.indexerLoop` | `core/filtermaps/indexer.go:35` | +2 −2 | ⚠️ none |
| 🟡 `NewFilterMaps` | `core/filtermaps/filtermaps.go:236` | +2 −1 | ✅ |
| 🟡 `FilterMaps.exportCheckpoints` | `core/filtermaps/filtermaps.go:881` | +3 −0 | ⚠️ none |
| 🟡 `FilterMaps.needTailEpoch` | `core/filtermaps/indexer.go:399` | +3 −0 | ⚠️ none |
| 🟡 `FilterMaps.setRange` | `core/filtermaps/filtermaps.go:490` | +1 −0 | ✅ |

</details>
