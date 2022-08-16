# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 5 | 5 | 6 | 3 | 19 |

- [Fail](#user-content-fail)
  - [❌ `apache-license-file`](#user-content--apache-license-file)
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
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Did not find file matching the specified patterns. (`LICENSE*`).

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

- `wrappers/node/notification-server.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-cli/logger.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-cli/script-common.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-cli/vcxclient-cli.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-cli/vcxclient-interactive.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/alice.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/faber.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/integration-test.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/logger.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/notification-server.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/script-common.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/wallet-common.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/agent.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/common.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/credential-def-v2.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/distribute-tails.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/feature-discovery.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/out-of-band.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/public-invite.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/sign-messaging.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/sign-verify.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/trustping.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/update-state-v2.spec.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-connections.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-cred-holder.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-cred-issuer.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-ledger-creddef.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-ledger-schema.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-out-of-band.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-prover.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-public-agents.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-revocation-registry.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-verifier.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/storage/storage-file.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/storage/storage-service.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/utils/credentials.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/utils/messages.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/utils/proofs.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/utils/vcx-workflows.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/utils/alice.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/utils/data.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/utils/faber.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/utils/utils.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/errors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/rustlib.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/vcx.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/module-resolver-helper.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/common.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/connection.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/credential-def.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/credential.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/disclosed-proof.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/init.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/issuer-credential.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/logging.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/out-of-band-receiver.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/out-of-band-sender.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/proof.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/public-agent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/revocation-registry.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/schema.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/vcx-base-with-state.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/vcx-base.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/vcx-mock.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/api/wallet.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/utils/error-message.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/utils/ffi-helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/src/utils/memory-management-helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/helpers/entities.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/helpers/test-constants.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/helpers/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-connection.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-credential-def.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-credential.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-disclosed-proof.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-issuer-credential.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-oob.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-proof.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-schema.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-utils.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite1/ariesvcx-wallet.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite2/ffi.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite3/logging.1.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/node/test/suite3/logging.2.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/demo/src/main/java/Alice.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/demo/src/main/java/Faber.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/demo/src/main/java/utils/Common.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/demo/src/main/java/utils/ProofState.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/demo/src/main/java/utils/VcxState.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/ActionNotSupportedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/ErrorCode.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/InvalidParameterException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/LibVcx.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/NoAgentInfoException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/ParamGuard.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/StringUtils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/VcxConstants.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/VcxException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/VcxJava.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/ConnectionApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/CredentialApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/CredentialDefApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/DisclosedProofApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/ErrorCodeTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/ProofApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/SchemaApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/TestHelper.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/VcxApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/VcxExceptionTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/VcxUtilsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/com/evernym/sdk/vcx/WalletApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/connection/ConnectionApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/connection/ConnectionErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/connection/InvalidConnectionHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/connection/InvalidInviteDetailsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/BuildCredentialDefReqErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/CreateCredentialDefException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/CreateCredentialRequestErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/CredentialApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/CredentialDefAlreadyCreatedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/GetCredentialCreateMsgidResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialDefHandle.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialDefJsonException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialJsonException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialRequestException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidIssuerCredentialHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credentialDef/CredentialDefApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/credentialDef/CredentialDefPrepareForEndorserResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/issuer/IssuerApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/CreateProofErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/CreateProofMsgIdResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/DisclosedProofApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/FailedProofComplianceException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/GetProofResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidDisclosedProofHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidProofCredentialDataException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidProofException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidProofHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidSelfAttestedValueException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/ProofApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/InvalidSchemaCreationException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/InvalidSchemaException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/InvalidSchemaSeqNoException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/InvalidSchemahandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/SchemaApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/SchemaPrepareForEndorserResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/token/InsufficientTokenAmountException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/token/TokenApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/utils/InvalidConfigurationException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/utils/PostMsgFailureException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/utils/UtilsApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/AlreadyInitializedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/BigNumberErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/CreatePoolConfigException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/IndySubmitRequestErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidAttributeStructureException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidDIDException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidGenesisTxnPathException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidHTTPResponseException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidJsonException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidKeyDelegateException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidMasterSecretException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidMessagesException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidMsgPackException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidNonceException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidObjHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidOptionException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidPredicateException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidUrlException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidVerkeyException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/NoEndpointException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/NoPoolOpenException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/NotBase58Exception.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/NotReadyException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/PoolLedgerConnectException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/SerializationErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/TimeoutLibindyErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/UnknownErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/UnknownLibindyErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/VcxApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletAccessFailedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletAleradyOpenException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletAlreadyExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletCreationException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletItemAlreadyExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletItemNotFoundException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.

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

### ✅ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Contains https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/main.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`aries_vcx/tests`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

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

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

