# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 5 | 3 | 7 | 4 | 19 |

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

- `app/baseapp.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/decoder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/grpcrouter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/grpcrouter_helpers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/grpcrouter_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/grpcserver.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/options.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/params.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chaincode/app.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chaincode/app_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chaincode/chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chaincode/chaincode_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chaincode/event_handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chaincode/packet_event_handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commitment/commitment.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commitment/commitment_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commitment/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commitment/key.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commitment/sequence.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commitment/sequence_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `example/app.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `store/dbadapter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `store/store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/util.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/fabibc/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/stub/stub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/compat/db.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/compat/db_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/compat/patch.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/auth/ante/ante.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/auth/types/context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/auth/types/creator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/testing/account.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/testing/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/testing/coordinator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/testing/fabric.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/testing/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/module.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/keeper/client_keeper.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/tests/util.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/client_state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/commitment.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/commitment_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/consensus_state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/errors.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/fabric.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/fabric_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/header.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/header_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/keys.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/msp.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/msp_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/proposal_handle.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/update.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `x/ibc/light-clients/xx-fabric/types/update_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.

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

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=javascript"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

