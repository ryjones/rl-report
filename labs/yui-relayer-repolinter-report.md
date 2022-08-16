# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 5 | 4 | 7 | 3 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

### ❌ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Doesn't contain license (`README.md`).

### ❌ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `MAINTAINERS.md`
- `MAINTAINERS.rst`

### ❌ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Did not find a file matching the specified patterns. (`CONTRIBUTING.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `tests/chains/ethereum/contract/truffle-config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/ethereum/contract/migrations/1_initial_migration.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/ethereum/contract/migrations/2_deploy_contracts.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/ethereum/contract/migrations/3_initialize_contract.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/chains.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/flags.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/paths.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/root.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/service.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/xfer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/marshaler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/module.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/channel.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/connection.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/headers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ics24.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/naive-strategy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/packet-tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/path.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/pathEnd.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/provers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/relayMsgs.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/service.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/strategies.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/utils.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/verifier.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `helpers/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `utils/marshaler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/create-client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/grpc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/prover.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/ethereum/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/ethereum/client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/ethereum/codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/ethereum/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/ethereum/events.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/ethereum/tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/ethereum/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/client-tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/commitment.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/fabric.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/gateway.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/proof.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/prover.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/wallet.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/client-tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/contextual.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/light.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/log-chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/prover.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `provers/mock/codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `provers/mock/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `provers/mock/prover.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/corda/module/module.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/ethereum/module/module.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/cmd/chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/cmd/cmd.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/cmd/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/cmd/flags.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/cmd/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/cmd/wallet.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/fabric/module/module.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/cmd/cmd.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/cmd/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/cmd/errors.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/cmd/flags.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/cmd/keys.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/cmd/light.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chains/tendermint/module/module.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `provers/mock/module/module.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/app.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/encoding.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/export.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/genesis.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/ibc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/test_helpers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/fabric/chaincode/fabibc/fabibc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/simd/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/simd/cmd/cmd_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/simd/cmd/genaccounts.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/simd/cmd/genaccounts_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/simd/cmd/root.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/chains/tendermint/simapp/simd/cmd/testnet.go`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/test.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`tests`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`go.mod`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: NOASSERTION.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

