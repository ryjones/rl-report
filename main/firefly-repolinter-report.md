# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 1 | 4 | 12 | 2 | 19 |

- [Fail](#user-content-fail)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Doesn't contain license (`README.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `docs/assets/js/just-the-docs.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/assets/js/versions.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `smart_contracts/ethereum/solidity_firefly/truffle-config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `smart_contracts/ethereum/solidity_firefly/test/Firefly.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `smart_contracts/ethereum/solidity_firefly/hardhat.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `smart_contracts/ethereum/solidity_firefly/scripts/deploy.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/apiservermocks/ffi_swagger_gen.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/apiservermocks/server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/assetmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/batchmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/blockchainmocks/callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/blockchainmocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/broadcastmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/contractmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/coremocks/operation_callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/databasemocks/callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/databasemocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/dataexchangemocks/callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/dataexchangemocks/dx_event.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/dataexchangemocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/datamocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/definitionsmocks/handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/definitionsmocks/sender.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/eventmocks/event_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/eventsmocks/callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/eventsmocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/identitymanagermocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/identitymocks/callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/identitymocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/metricsmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/multipartymocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/namespacemocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/networkmapmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/operationmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/orchestratormocks/orchestrator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/privatemessagingmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/shareddownloadmocks/callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/shareddownloadmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/sharedstoragemocks/callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/sharedstoragemocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/spieventsmocks/manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/syncasyncmocks/bridge.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/syncasyncmocks/sender.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/systemeventmocks/event_interface.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/tokenmocks/callbacks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/tokenmocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/txcommonmocks/helper.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `mocks/wsmocks/ws_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `smart_contracts/fabric/firefly-go/firefly.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `smart_contracts/fabric/firefly-go/chaincode/contract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `smart_contracts/fabric/firefly-go/chaincode/contract_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `test/data/contracts/assetcreator/assetCreator.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `test/data/contracts/assetcreator/chaincode/smartcontract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `pom.xml`
- `build.xml`
- `build.gradle`

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

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/docker_main.yml`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`test`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`go.mod`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

