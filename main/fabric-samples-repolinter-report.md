# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 0 | 5 | 12 | 2 | 19 |

- [Warning](#user-content-warning)
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
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
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

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `token-erc-20/chaincode-javascript/index.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-javascript/index.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-javascript/test/assetTransfer.test.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-events/chaincode-javascript/test/assetTransferEvents.test.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-ledger-queries/chaincode-javascript/lib/asset_transfer_ledger_chaincode.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-javascript/lib/tokenERC20.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-javascript/test/tokenERC20.test.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-javascript/lib/tokenERC721.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-javascript/test/tokenERC721.test.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/application/cpListener.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commercial-paper/organization/digibank/contract/lib/queries.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract/lib/queries.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-abac/chaincode-go/smartContract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-external/assetTransfer.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-go/assetTransfer.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-ledger-queries/chaincode-go/asset_transfer_ledger_chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-private-data/chaincode-go/main.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-secured-agreement/chaincode-go/asset_transfer.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-secured-agreement/chaincode-go/asset_transfer_queries.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction/chaincode-go/smartContract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-go/token_erc_20.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-utxo/chaincode-go/token_utxo.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-abac/chaincode-go/smart-contract/abac.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-basic/chaincode-go/chaincode/smartcontract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-basic/chaincode-go/chaincode/smartcontract_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `auction/chaincode-go/smart-contract/auction.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction/chaincode-go/smart-contract/auctionQueries.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction/chaincode-go/smart-contract/utils.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/external/fabcar.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/go/fabcar.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/marbles02/go/marbles_chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-go/chaincode/token_contract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `token-utxo/chaincode-go/chaincode/token_contract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-basic/chaincode-go/chaincode/mocks/chaincodestub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-basic/chaincode-go/chaincode/mocks/statequeryiterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-basic/chaincode-go/chaincode/mocks/transaction.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-private-data/chaincode-go/chaincode/mocks/chaincodestub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-private-data/chaincode-go/chaincode/mocks/clientIdentity.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-private-data/chaincode-go/chaincode/mocks/statequeryiterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-private-data/chaincode-go/chaincode/mocks/transaction.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commercial-paper/organization/digibank/contract-go/main.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/main.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/commercial-paper/paper.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/commercial-paper/paper_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/commercial-paper/papercontext.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/commercial-paper/papercontext_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/commercial-paper/papercontract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/commercial-paper/papercontract_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/commercial-paper/paperlist.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/commercial-paper/paperlist_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/ledger-api/state.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-go/ledger-api/statelist.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/commercial-paper/paper.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/commercial-paper/paper_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/commercial-paper/papercontext.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/commercial-paper/papercontext_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/commercial-paper/papercontract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/commercial-paper/papercontract_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/commercial-paper/paperlist.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/commercial-paper/paperlist_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/ledger-api/state.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-go/ledger-api/statelist.go`: The first 7 lines do not contain the pattern(s): Copyright.

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

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`ci/azure-pipelines.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`test-application`).

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

