# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 1 | 3 | 11 | 4 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
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


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `packages/rest/bin/afj-rest.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `jest.config.base.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `scripts/getPackages.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/react-hooks/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/samples/sample.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/tests/pushNotificationsApnsService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/tests/pushNotificationsFcmService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/react-hooks/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/react-hooks/src/recordUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/react-hooks/tests/index.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/recordListener.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/store.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/types.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/tests/index.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/samples/sample.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/samples/sampleWithApp.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/cli.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/cliAgent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/server.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/agent.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/basicMessage.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/connection.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/credential.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/credentialDefinition.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/proof.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/schema.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/webhook.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/modules/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/tests/utils/agent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/agent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/samples/utils/GreetingController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/events/BasicMessageEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/events/ConnectionEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/events/CredentialEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/events/ProofEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/events/WebhookEvent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/AcceptCredentialProposalRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/AcceptProofProposalRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/BasicMessageRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/CredentialDefinitionRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/CredentialOfferRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/CredentialOfferTemplate.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/CredentialProposalRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/InvitationConfigRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/InvitationRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/PresentationProofRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/ProofPresentationRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/ProofProposalRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/ProofRequestTemplate.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/ReceiveInvitationByUrlRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/ReceiveInvitationRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/schemas/SchemaRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/utils/ProofRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/utils/ServerConfig.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/utils/TsyringeAdapter.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/utils/logger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/utils/agent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/utils/helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/utils/util.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/tests/utils/webhook.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/apns/PushNotificationsApnsDeviceInfoHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/apns/PushNotificationsApnsGetDeviceInfoHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/apns/PushNotificationsApnsSetDeviceInfoHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/apns/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/fcm/PushNotificationsFcmDeviceInfoHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/fcm/PushNotificationsFcmGetDeviceInfoHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/fcm/PushNotificationsFcmSetDeviceInfoHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/handlers/fcm/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/apns/PushNotificationsApnsDeviceInfoMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/apns/PushNotificationsApnsGetDeviceInfoMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/apns/PushNotificationsApnsSetDeviceInfoMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/apns/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/fcm/PushNotificationsFcmDeviceInfoMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/fcm/PushNotificationsFcmGetDeviceInfoMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/fcm/PushNotificationsFcmSetDeviceInfoMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/messages/fcm/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/modules/apns/PushNotificationsApnsModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/modules/apns/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/modules/fcm/PushNotificationsFcmModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/modules/fcm/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/services/apns/ApnsDeviceInfo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/services/apns/PushNotificationsApnsService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/services/apns/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/services/fcm/FcmDeviceInfo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/services/fcm/PushNotificationsFcmService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/push-notifications/src/services/fcm/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/connections/connectionsSelectors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/connections/connectionsSlice.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/connections/connectionsThunks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/connections/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/credentials/credentialsSelectors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/credentials/credentialsSlice.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/credentials/credentialsThunks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/credentials/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/mediation/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/mediation/mediationSelectors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/mediation/mediationSlice.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/mediation/mediationThunks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/proofs/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/proofs/proofsSelectors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/proofs/proofsSlice.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/redux-store/src/slices/proofs/proofsThunks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/controllers/agent/AgentController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/controllers/basic-messages/BasicMessageController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/controllers/connections/ConnectionController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/controllers/credentials/CredentialController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/controllers/credentials/CredentialDefinitionController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/controllers/credentials/SchemaController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/rest/src/controllers/proofs/ProofController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE`).

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

Found file (`.github/workflows/codeql-analysis.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`packages/push-notifications/tests`).

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

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=go"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

