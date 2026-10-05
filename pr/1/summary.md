<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/1/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 12 | +1093 / −67 | 35 / 23 / 0 | 133 / 9 | 58% (14/24) |

<details><summary>Largest changed functions (48 total)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟢 `TestForkchoiceHeadFetchQueue` | `eth/catalyst/api_test.go:2313` | +142 −0 | — |
| 🟡 `engineClient.updateLoop` | `beacon/blsync/engineclient.go:92` | +61 −19 | ✅ |
| 🟢 `TestBlockSyncP2PBlocksFallback` | `beacon/blsync/block_sync_test.go:230` | +73 −0 | — |
| 🟢 `TestBlockSyncP2PBlocks` | `beacon/blsync/block_sync_test.go:164` | +62 −0 | — |
| 🟡 `ConsensusAPI.forkchoiceUpdated` | `eth/catalyst/api.go:356` | +17 −25 | ✅ |
| 🟢 `TestEngineClientFallbackPause` | `beacon/blsync/engineclient_test.go:288` | +39 −0 | — |
| 🟢 `ConsensusAPI.fetchHead` | `eth/catalyst/api.go:180` | +36 −0 | ✅ |
| 🟡 `beaconBlockSync.updateEventFeed` | `beacon/blsync/block_sync.go:186` | +25 −5 | ⚠️ none |
| 🟢 `beaconBlockSync.updateFallback` | `beacon/blsync/block_sync.go:130` | +28 −0 | ⚠️ none |
| 🟢 `newEngineTest` | `beacon/blsync/engineclient_test.go:99` | +27 −0 | — |

</details>
