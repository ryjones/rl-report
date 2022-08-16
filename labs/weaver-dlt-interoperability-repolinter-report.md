# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 0 | 6 | 11 | 2 | 19 |

- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `samples/besu/simpleasset/get-network-details.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/simpleasset/truffle-config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/simpleasset/app/AssetExchangeERC20.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/simpleasset/migrations/1_initial_migration.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/simpleasset/migrations/2_deploy_contracts.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/network-setups/besu/artifacts/network1/createKeyFile.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/network-setups/besu/artifacts/network2/createKeyFile.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/__tests__/cli-integration.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/cli.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/types.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/identity-management/iin-agent/src/common/ledgerBase.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/besu-cli.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/generate.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/extensions/cli-extension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/helper/besu-functions.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/helper/helper.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/asset/claim.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/asset/exchange.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/asset/get-balance.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/asset/is-locked.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/asset/issue.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/asset/lock.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/besu/besu-cli/src/commands/asset/unlock.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleasset/assetmgmt_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleasset/bondasset.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleasset/bondasset_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleasset/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleasset/tokenasset.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleasset/tokenasset_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassetandinterop/assetmgmt_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassetandinterop/baseclass.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassetandinterop/bondasset.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassetandinterop/bondasset_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassetandinterop/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassetandinterop/tokenasset.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassetandinterop/tokenasset_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassettransfer/assetPledgeMap.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassettransfer/assetmgmt_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassettransfer/bondasset.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassettransfer/bondasset_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassettransfer/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassettransfer/tokenasset.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simpleassettransfer/tokenasset_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simplestate/simplestate_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/fabric/simplestatewithacl/simplestate_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/network/fabric-interop-cc/interfaces/asset-mgmt/asset_locks_contract_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`go.mod`).

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

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/deploy_corda-pkgs.yml`).

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

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

