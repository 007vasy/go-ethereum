<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/3/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 6 | +341 / −17 | 7 / 15 / 0 | 47 / 0 | 29% (2/7) |

<details><summary>Largest changed functions (17 total)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟢 `TestIndexerHistoryCutoff` | `core/filtermaps/cutoff_test.go:35` | +74 −0 | — |
| 🟢 `testSetup.checkCutoffIndex` | `core/filtermaps/cutoff_test.go:179` | +74 −0 | — |
| 🟡 `FilterMaps.init` | `core/filtermaps/filtermaps.go:378` | +29 −8 | ⚠️ none |
| 🟢 `TestFilterMapsRangeLocalBase` | `core/rawdb/accessors_indexes_test.go:303` | +25 −0 | — |
| 🟢 `TestIndexerHistoryCutoffRandom` | `core/filtermaps/cutoff_test.go:152` | +24 −0 | — |
| 🟢 `TestIndexerHistoryCutoffExport` | `core/filtermaps/cutoff_test.go:131` | +18 −0 | — |
| 🟢 `TestIndexerHistoryCutoffBlock` | `core/filtermaps/cutoff_test.go:112` | +16 −0 | — |
| 🟡 `FilterMaps.tryUnindexTail` | `core/filtermaps/indexer.go:361` | +5 −0 | ⚠️ none |
| 🟡 `testChain.GetRawReceipts` | `core/filtermaps/indexer_test.go:527` | +1 −4 | — |
| 🟡 `FilterMaps.indexerLoop` | `core/filtermaps/indexer.go:35` | +2 −2 | ⚠️ none |

</details>
