# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 0 | 2 | 12 | 5 | 19 |

- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `integration/burrow/simple.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/balances.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/builtins.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/calls.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/create_contract.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/errors.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/events.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/oznfc.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/setup.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/simple.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/token.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/solana/verify_sig.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/UniswapV2ERC20.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/UniswapV2Factory.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/UniswapV2Pair.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/array_struct_mapping_storage.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/arrays.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/asserts.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/balances.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/builtins.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/builtins2.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/create_contract.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/destruct.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/events.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/external_call.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/flipper.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/issue666.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/msg_sender.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/primitives.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/randomizer.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/store.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/substrate/structs.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/client/extension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/server/server.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/test/runTest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/utils/download.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/utils/downloadFile.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/utils/downloadWithRetryDialog.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/utils/executableVersion.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/utils/expandPathResolving.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/utils/fetchLatestRelease.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/utils/getPlatform.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/utils/getServer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/test/suite/extension.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/test/suite/helper.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vscode/src/test/suite/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE`).

### ✅ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Contains https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).

### ✅ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Contains https://wiki.hyperledger.org/display/.*(SEC|HYP)/Defect[.+]Response (`SECURITY.md`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/build-llvm.yml`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`tests`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=javascript"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=go"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

