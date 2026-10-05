<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/4/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 2 | +305 / −25 | 6 / 3 / 0 | 23 / 2 | 100% (5/5) |

<details><summary>Largest changed functions (7 total)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟢 `TestForkchoiceHeadFetchQueue` | `eth/catalyst/api_test.go:2313` | +142 −0 | — |
| 🟡 `ConsensusAPI.forkchoiceUpdated` | `eth/catalyst/api.go:356` | +17 −25 | ✅ |
| 🟢 `ConsensusAPI.fetchHead` | `eth/catalyst/api.go:180` | +36 −0 | ✅ |
| 🟢 `TestSyncFetchedHeadSuperseded` | `eth/catalyst/api_test.go:2280` | +27 −0 | — |
| 🟢 `ConsensusAPI.beaconSync` | `eth/catalyst/api.go:248` | +21 −0 | ✅ |
| 🟢 `ConsensusAPI.syncFetchedHead` | `eth/catalyst/api.go:234` | +12 −0 | ✅ |
| 🟢 `ConsensusAPI.fetchHeader` | `eth/catalyst/api.go:218` | +6 −0 | ✅ |

</details>
