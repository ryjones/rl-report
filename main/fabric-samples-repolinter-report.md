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
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
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

- `token-erc-721/chaincode-javascript/index.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-javascript/lib/tokenERC721.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-javascript/test/tokenERC721.test.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-basic/chaincode-typescript/src/asset.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-typescript/src/assetTransfer.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-typescript/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/assets.router.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/auth.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/config.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/config.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/errors.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/errors.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/fabric.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/fabric.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/health.router.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/jobs.router.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/jobs.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/jobs.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/logger.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/redis.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/redis.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/server.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/transactions.router.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-sbe/chaincode-typescript/src/asset.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-sbe/chaincode-typescript/src/assetContract.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-sbe/chaincode-typescript/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabcar/typescript/src/enrollAdmin.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabcar/typescript/src/invoke.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabcar/typescript/src/query.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabcar/typescript/src/registerUser.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/rest-api-typescript/src/__tests__/api.test.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/typescript/src/car.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/typescript/src/fabcar.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/typescript/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-abac/chaincode-go/smartContract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-external/assetTransfer.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-go/assetTransfer.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-ledger-queries/chaincode-go/asset_transfer_ledger_chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-private-data/chaincode-go/main.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-secured-agreement/chaincode-go/asset_transfer.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-secured-agreement/chaincode-go/asset_transfer_queries.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-dutch/chaincode-go/smartContract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-dutch/chaincode-go-auditor/smartContract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-simple/chaincode-go/smartContract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-1155/chaincode-go/erc1155.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-go/token_erc_20.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-go/main.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-utxo/chaincode-go/token_utxo.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-abac/chaincode-go/smart-contract/abac.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-basic/chaincode-go/chaincode/smartcontract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-basic/chaincode-go/chaincode/smartcontract_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `auction-dutch/chaincode-go/smart-contract/auction.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-dutch/chaincode-go/smart-contract/auctionQueries.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-dutch/chaincode-go/smart-contract/utils.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-dutch/chaincode-go-auditor/smart-contract/auction.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-dutch/chaincode-go-auditor/smart-contract/auctionQueries.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-dutch/chaincode-go-auditor/smart-contract/utils.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-simple/chaincode-go/smart-contract/auction.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-simple/chaincode-go/smart-contract/auctionQueries.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `auction-simple/chaincode-go/smart-contract/utils.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/external/fabcar.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/go/fabcar.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/marbles02/go/marbles_chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-1155/chaincode-go/chaincode/contract.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-go/chaincode/token_contract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `token-erc-721/chaincode-go/chaincode/erc721-contract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `token-erc-721/chaincode-go/chaincode/erc721-contract_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `token-erc-721/chaincode-go/chaincode/erc721.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-utxo/chaincode-go/chaincode/token_contract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
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
- `asset-transfer-basic/application-java/src/main/java/application/java/RegisterUser.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-ledger-queries/application-java/src/main/java/application/java/RegisterUser.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/application-java/src/org/digibank/AddToWallet.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/application-java/src/org/digibank/Buy.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/application-java/src/org/digibank/Redeem.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/application-java/src/org/papernet/CommercialPaper.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/application-java/src/org/magnetocorp/AddToWallet.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/application-java/src/org/magnetocorp/Issue.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/application-java/src/org/papernet/CommercialPaper.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabcar/java/src/main/java/org/example/ClientApp.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabcar/java/src/main/java/org/example/EnrollAdmin.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabcar/java/src/main/java/org/example/RegisterUser.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabcar/java/src/test/java/org/example/ClientTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/application-java/src/org/papernet/ledgerapi/State.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/application-java/src/org/papernet/ledgerapi/State.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-java/src/main/java/org/example/CommercialPaper.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-java/src/main/java/org/example/CommercialPaperContext.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commercial-paper/organization/digibank/contract-java/src/main/java/org/example/CommercialPaperContract.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-java/src/main/java/org/example/PaperList.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-java/src/main/java/org/example/CommercialPaper.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-java/src/main/java/org/example/CommercialPaperContext.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commercial-paper/organization/magnetocorp/contract-java/src/main/java/org/example/CommercialPaperContract.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-java/src/main/java/org/example/PaperList.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-java/src/main/java/org/hyperledger/fabric/samples/assettransfer/Asset.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-java/src/main/java/org/hyperledger/fabric/samples/assettransfer/AssetTransfer.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-java/src/test/java/org/hyperledger/fabric/samples/assettransfer/AssetTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-basic/chaincode-java/src/test/java/org/hyperledger/fabric/samples/assettransfer/AssetTransferTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-events/chaincode-java/src/main/java/org/hyperledger/fabric/samples/events/Asset.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-events/chaincode-java/src/main/java/org/hyperledger/fabric/samples/events/AssetTransfer.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-private-data/chaincode-java/src/main/java/org/hyperledger/fabric/samples/privatedata/Asset.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-private-data/chaincode-java/src/main/java/org/hyperledger/fabric/samples/privatedata/AssetPrivateDetails.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-private-data/chaincode-java/src/main/java/org/hyperledger/fabric/samples/privatedata/AssetTransfer.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-private-data/chaincode-java/src/main/java/org/hyperledger/fabric/samples/privatedata/TransferAgreement.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `asset-transfer-private-data/chaincode-java/src/test/java/org/hyperledger/fabric/samples/privatedata/AssetTransferTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-sbe/chaincode-java/src/main/java/org/hyperledger/fabric/samples/sbe/Asset.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `asset-transfer-sbe/chaincode-java/src/main/java/org/hyperledger/fabric/samples/sbe/AssetContract.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-java/src/main/java/org/example/ledgerapi/State.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-java/src/main/java/org/example/ledgerapi/StateDeserializer.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commercial-paper/organization/digibank/contract-java/src/main/java/org/example/ledgerapi/StateList.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commercial-paper/organization/magnetocorp/contract-java/src/main/java/org/example/ledgerapi/State.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/magnetocorp/contract-java/src/main/java/org/example/ledgerapi/StateDeserializer.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commercial-paper/organization/magnetocorp/contract-java/src/main/java/org/example/ledgerapi/StateList.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `token-erc-20/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc20/ContractConstants.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc20/ContractErrors.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc20/ERC20TokenContract.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-java/src/test/java/org/hyperledger/fabric/samples/erc20/TokenERC20ContractTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc721/ContractConstants.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc721/ContractErrors.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc721/ERC721TokenContract.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-java/src/test/java/org/hyperledger/fabric/samples/erc721/ERC721TokenContractTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chaincode/fabcar/java/src/main/java/org/hyperledger/fabric/samples/fabcar/Car.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/java/src/main/java/org/hyperledger/fabric/samples/fabcar/CarQueryResult.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/java/src/main/java/org/hyperledger/fabric/samples/fabcar/FabCar.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/java/src/test/java/org/hyperledger/fabric/samples/fabcar/CarQueryResultTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/java/src/test/java/org/hyperledger/fabric/samples/fabcar/CarTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `chaincode/fabcar/java/src/test/java/org/hyperledger/fabric/samples/fabcar/FabCarTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `commercial-paper/organization/digibank/contract-java/src/main/java/org/example/ledgerapi/impl/StateListImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `commercial-paper/organization/magnetocorp/contract-java/src/main/java/org/example/ledgerapi/impl/StateListImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `token-erc-20/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc20/model/Approval.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc20/model/Transfer.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-20/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc20/utils/ContractUtility.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc721/models/Approval.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc721/models/NFT.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc721/models/Transfer.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `token-erc-721/chaincode-java/src/main/java/org/hyperledger/fabric/samples/erc721/utils/ContractUtility.java`: The first 7 lines do not contain the pattern(s): Copyright.

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

Found file (`ci/azure-pipelines.yml`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

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

