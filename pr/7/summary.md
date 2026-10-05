<!-- graph-diff -->
### ◆ graph-diff — [open the 3D call-graph diff](https://007vasy.github.io/go-ethereum/pr/7/)

| files | lines | functions (+ / ~ / −) | call edges (+ / −) | test reach |
|---|---|---|---|---|
| 3 | +52 / −9 | 3 / 5 / 0 | 4 / 0 | 33% (1/3) |

⚠️ **2 changed functions not reached by any test:** `KeyStore.Delete`, `accountCache.deleteFile`

<details><summary>Largest changed functions (3 in code, 2 in tests)</summary>

| function | location | lines | test reach |
|---|---|---|---|
| 🟡 `KeyStore.Delete` | `accounts/keystore/keystore.go:233` | +4 −8 | ⚠️ none |
| 🟢 `accountCache.deleteFile` | `accounts/keystore/account_cache.go:135` | +10 −0 | ⚠️ none |
| 🟡 `accountCache.scanAccounts` | `accounts/keystore/account_cache.go:255` | +3 −0 | ✅ |

</details>
