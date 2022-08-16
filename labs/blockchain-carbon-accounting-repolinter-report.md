# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 5 | 5 | 7 | 2 | 19 |

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

- `fabric/docker-compose-setup/abrevToName.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/docker-compose-setup/egrid-data-loader.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/typescript_app/webpack.config.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/deploy/dao.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/deploy/daoToken.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/deploy/net-emissions-token-network.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/deploy/z-carbon-tracker.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/hedera/deploy.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `hardhat/test/DAO-integration-tests.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/test/DAO-multi-attribute-tests.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/test/DAO-unit-tests.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/test/common.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/test/ethers-provider.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `hardhat/test/token-network-integration-tests.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `hardhat/test/token-network-unit-tests.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `open-offsets-directory/node-server/server.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/frontend/react-app/config-overrides.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/react/src/App.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/react/src/http-common.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/react/src/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/react/src/serviceWorker.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/identity-ui/src/App.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/identity-ui/src/Routes.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/identity-ui/src/history.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/identity-ui/src/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/frontend/react-app/scripts/ipfs.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `app/supply-chain/api/test/test.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/config/db.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/controllers/issuance.controller.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/controllers/project.controller.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/controllers/project_rating.controller.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/controllers/project_registry.controller.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/controllers/retirement.controller.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/middlewares/recaptcha.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/models/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/models/issuance.model.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/models/project.model.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/models/project_rating.model.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/models/project_registry.model.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/models/retirement.model.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/routes/issuance.routes.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/routes/project.routes.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/routes/project_rating.routes.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/routes/project_registry.routes.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/node-server/app/routes/retirement.routes.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/react/src/components/project-view.component.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/react/src/components/projects-list.component.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `open-offsets-directory/react/src/services/project.service.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/identity-ui/src/Home/Home.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/identity-ui/src/Utils/Common.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/identity-ui/src/Vault/Vault.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `hardhat/hardhat.config.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `app/api-server/server.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/typings.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/supply-chain/emissions.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/dataLoader.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/getData.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/postgresDbService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/test/wallet-unit-tests.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `hardhat/test/bigint-tests.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `hardhat/test/emissions-factor-unit-tests.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `hardhat/test/token-request-integration-tests.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/data-common/abbrevToName.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/data-common/db.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/data-common/spreadsheetImport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/data-common/uom.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/data-common/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/oil-and-gas-data/import.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity/app.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/components/event.listener.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/controller/balance.controller.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/controller/emissionsRequests.controller.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/controller/product.controller.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/controller/signedMessage.controller.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/controller/synchronizer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/controller/token.controller.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/controller/wallet.controller.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/middleware/base.middle.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/middleware/query.middle.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/models/commonTypes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/router/router.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/trpc/balance.trpc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/trpc/common.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/trpc/emissions-factors.trpc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/trpc/emissions-requests.trpc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/trpc/product-token.trpc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/trpc/token.trpc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/trpc/wallet.trpc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/utils/email.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/utils/errors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/utils/rateLimiter.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/api-server/utils/web3.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/supply-chain/api/server.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/app.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/tests/e2e.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/tests/setup-ws.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/tests/setup.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/api/postgresApi.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/activityEmissionsFactorLookup.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/balance.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/bigint_transformer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/emissionsFactor.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/emissionsRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/oilAndGasAsset.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/product.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/productToken.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/sync.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/token.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/tracker.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/uploadedFile.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/utilityLookupItem.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/models/wallet.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/activityEmissionsFactorLookup.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/balance.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/common.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/emissionsFactor.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/emissionsRequest.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/file.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/oilAndGasAsset.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/product.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/productToken.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/token.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/tracker.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/utilityLookupItem.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `data/src/repositories/wallet.repo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/emissions_data/src/const.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `lib/emissions_data/src/emissions-calc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/emissions_data/src/emissionsFactor.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/emissions_data/src/utilityLookupItem.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/oil-and-gas-data/src/oilAndGasAsset.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/oil-and-gas-data/src/product.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/supply-chain/src/common-types.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/supply-chain/src/crypto-utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/supply-chain/src/distance-utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/supply-chain/src/emissions-utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/supply-chain/src/ipfs-utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/supply-chain/src/ups-types.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/supply-chain/src/ups-utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/app.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/test/setup.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity/src/client.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity/src/router.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity/src/server.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity-client/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity-client/tests/index.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-wallet/bin/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-wallet/bin/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-wallet/src/app.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-wallet/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-wallet/src/router.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-wallet/src/util.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-wallet/src/wallet.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/frontend/contracts/src/abis.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `app/frontend/contracts/src/addresses.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `app/frontend/contracts/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `app/frontend/react-app/src/setupTests.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/typescript_app/src/blockchain-gateway/datalock.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/blockchain-gateway/emissionsChannel.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/blockchain-gateway/fabricRegistry.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/controllers/emissionsChannel.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/controllers/identity.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/controllers/registerEnroll.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/datasource/awsS3.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/errors/clientError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/service/emissionsChannel.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/service/fabricRegistry.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/service/input.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/service/service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/utils/dateUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/typescript_app/src/utils/logger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/tests/blockchain-gateway/datalock.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/tests/blockchain-gateway/emissionsChannel.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/tests/blockchain-gateway/fabric-registry.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/tests/blockchain-gateway/netEmissionsTokenNetwork.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/tests/blockchain-gateway/signer.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/blockchain-gateway/src/blockchain-gateway/I-gateway.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/blockchain-gateway/src/blockchain-gateway/config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/blockchain-gateway/src/blockchain-gateway/netEmissionsTokenNetwork.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/blockchain-gateway/src/blockchain-gateway/signer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/blockchain-gateway/src/errors/clientError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `lib/blockchain-gateway/src/utils/logger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/service/vault.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/utils/logger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/utils/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity/src/routers/client.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/ws-identity/src/routers/session.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/frontend/react-app/src/services/api.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/frontend/react-app/src/services/api.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/frontend/react-app/src/services/contract-functions.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `app/frontend/react-app/src/services/fabric-api.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `app/frontend/react-app/src/services/trpc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/supply-chain/api/app/controllers/controller.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/supply-chain/api/app/routers/router.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/emissionscontract/typescript/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/routers/v1/emissionsChannel.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/routers/v1/identity.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/routers/v1/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/typescript_app/src/routers/v1/registerEnroll.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/emissionscontract/typescript/src/lib/emissions-calc.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/emissionscontract/typescript/src/lib/emissions.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/emissionscontract/typescript/src/lib/emissionsFactor.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/emissionscontract/typescript/src/lib/emissionsRecordContract.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/emissionscontract/typescript/src/lib/utilityLookupItem.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/emissionscontract/typescript/src/util/const.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/emissionscontract/typescript/src/util/state.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/emissionscontract/typescript/src/util/util.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/emissionscontract/typescript/src/util/worldstate.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/emissionscontract/typescript/test/lib/emissions-calc.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/emissionscontract/typescript/test/lib/emissionsFactor.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/delivery/http/v1/identity.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/delivery/http/v1/key.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/delivery/http/v1/secrets.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/delivery/http/v1/token.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `secure-identities/vault-identity/src/delivery/http/v1/v1.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/multi-cloud-deployment/chaincode/marbles02.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/datalock/internal/chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/lock-state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/lock-state_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/locker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/locker_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/method.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/method_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/tx_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/internal/util_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/mock/emissionsCC.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/model/data-chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/model/transaction.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/model/tx-io.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/multi-cloud-deployment/deploy-aws/chaincode/marbles02.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `fabric/chaincode/datalock/pkg/errors/code.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/pkg/errors/errors.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fabric/chaincode/datalock/pkg/logger/logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`go.mod`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `setup.py`
- `requirements.txt`

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/ci.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`data/test`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`package.json`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

</details>

