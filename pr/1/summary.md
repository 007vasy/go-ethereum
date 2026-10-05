<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/1/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 12 | +1093 / −67 | 35 / 23 / 0 | 133 / 9 | 58% (14/24) |

⚠️ **10 changed functions not reached by any test:** `beaconBlockSync.updateEventFeed`, `beaconBlockSync.updateFallback`, `startEngineClient`, `beaconBlockSync.tryRequestBlock`, `beaconBlockSync.Process`, `Client.Start`, `beaconBlockSync.parentSlot`, `NewClient`, …

<details><summary>Largest changed functions (24 in code, 24 in tests)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟡 `engineClient.updateLoop` | `beacon/blsync/engineclient.go:92` | +61 −19 | ✅ |
| 🟡 `ConsensusAPI.forkchoiceUpdated` | `eth/catalyst/api.go:356` | +17 −25 | ✅ |
| 🟢 `ConsensusAPI.fetchHead` | `eth/catalyst/api.go:180` | +36 −0 | ✅ |
| 🟡 `beaconBlockSync.updateEventFeed` | `beacon/blsync/block_sync.go:186` | +25 −5 | ⚠️ none |
| 🟢 `beaconBlockSync.updateFallback` | `beacon/blsync/block_sync.go:130` | +28 −0 | ⚠️ none |
| 🟢 `ConsensusAPI.beaconSync` | `eth/catalyst/api.go:248` | +21 −0 | ✅ |
| 🟢 `engineClient.forkchoiceUpdated` | `beacon/blsync/engineclient.go:201` | +20 −0 | ✅ |
| 🟢 `engineClient.sendHead` | `beacon/blsync/engineclient.go:183` | +15 −0 | ✅ |
| 🟢 `startEngineClientWithClock` | `beacon/blsync/engineclient.go:54` | +14 −0 | ✅ |
| 🟡 `startEngineClient` | `beacon/blsync/engineclient.go:50` | +2 −11 | ⚠️ none |

</details>
