<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/5/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 8 | +204 / −26 | 6 / 12 / 0 | 26 / 0 | 100% (13/13) |

<details><summary>Largest changed functions (13 in code, 2 in tests)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟡 `stateTransition.preCheck` | `core/state_transition.go:573` | +9 −3 | ✅ |
| 🟡 `TransactionArgs.ToMessage` | `internal/ethapi/transaction_args.go:467` | +5 −3 | ✅ |
| 🟢 `Message.SkipNonceCheck` | `core/state_transition.go:303` | +4 −0 | ✅ |
| 🟢 `Message.SkipEOACheck` | `core/state_transition.go:309` | +4 −0 | ✅ |
| 🟢 `Message.SkipGasLimitCapCheck` | `core/state_transition.go:316` | +4 −0 | ✅ |
| 🟢 `Message.SkipExecutionGasCapCheck` | `core/state_transition.go:324` | +4 −0 | ✅ |
| 🟡 `applyMessage` | `internal/ethapi/api.go:793` | +2 −1 | ✅ |
| 🟡 `simulator.processBlock` | `internal/ethapi/simulate.go:259` | +3 −0 | ✅ |
| 🟡 `statePrefetcher.Prefetch` | `core/state_prefetcher.go:53` | +1 −1 | ✅ |
| 🟡 `TransactionToMessage` | `core/state_transition.go:330` | +0 −2 | ✅ |

</details>
