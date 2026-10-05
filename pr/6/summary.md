<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/6/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 3 | +229 / −0 | 8 / 2 / 0 | 18 / 0 | 75% (3/4) |

<details><summary>Largest changed functions (8 total)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟢 `TestDropEnvVarsShadowedByArgs` | `internal/flags/helpers_test.go:34` | +64 −0 | — |
| 🟢 `flagsPresentInArgs` | `internal/flags/helpers.go:304` | +34 −0 | ✅ |
| 🟢 `DropEnvVarsShadowedByArgs` | `internal/flags/helpers.go:274` | +25 −0 | ✅ |
| 🟢 `TestIntFlagCLIOverridesInvalidEnv` | `internal/flags/helpers_test.go:99` | +22 −0 | — |
| 🟢 `TestIntFlagInvalidEnvStillErrorsWithoutCLI` | `internal/flags/helpers_test.go:122` | +15 −0 | — |
| 🟢 `splitFlagArg` | `internal/flags/helpers.go:341` | +13 −0 | ✅ |
| 🟢 `testAppFlags` | `internal/flags/helpers_test.go:26` | +7 −0 | — |
| 🟡 `main` | `cmd/geth/main.go:287` | +3 −0 | ⚠️ none |

</details>
