# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 3 | 6 | 9 | 1 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Doesn't contain license (`README.md`).

### ❌ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Did not find a file matching the specified patterns. (`CONTRIBUTING.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `samples/nodejs/src/anoncredsRevocation.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/nodejs/src/anoncredsRevocationScenario.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/nodejs/src/colors.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/nodejs/src/gettingStarted.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/nodejs/src/main.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/nodejs/src/util.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/notification-server.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/IndyError.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/indyBinding.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/wrapIndyCallback.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/anoncreds.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/blob.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/cache.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/crypto.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/did.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/ledger.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/logger.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/logger2.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/mod.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/nonsecrets.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/pairwise.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/payments.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/pool.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/wallet.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/nodejs/colors.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/nodejs/negotiateProof.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/nodejs/step2.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/nodejs/step3.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/nodejs/step4.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/nodejs/step5.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/nodejs/template.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/nodejs/util.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/nodejs/colors.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/nodejs/rotateKey.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/nodejs/step2.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/nodejs/step3.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/nodejs/step4.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/nodejs/template.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/nodejs/util.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/nodejs/colors.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/nodejs/step2.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/nodejs/step3.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/nodejs/step4.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/nodejs/step5.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/nodejs/template.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/nodejs/util.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/nodejs/writeDidAndQueryVerkey.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/demo/alice-signature.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/demo/alice.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/demo/common.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/demo/faber-verify-signature.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/demo/faber.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/demo/logger.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/demo/script-comon.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/dotnet/docs/styles/docfx.vendor.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `wrappers/dotnet/docs/styles/search-worker.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/helpers/initTestPool.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/helpers/makeTestPool.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/errors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/rustlib.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/vcx.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/module-resolver-helper.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/common.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/connection.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/credential-def.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/credential.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/disclosed-proof.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/init.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/issuer-credential.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/logging.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/proof.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/schema.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/vcx-base-with-state.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/vcx-base.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/vcx-mock.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/vcx-payment-txn.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/api/wallet.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/utils/error-message.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/utils/ffi-helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/src/utils/memory-management-helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/helpers/asserts.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/helpers/entities.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/helpers/test-constants.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/helpers/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/connection.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/credential-def.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/credential.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/disclosed-proof.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/issuer-credential.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/proof.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/schema.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/utils.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite1/wallet.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite2/ffi.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite3/logging.1.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/node/test/suite3/logging.2.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/issue-credential/java/IssueCredential.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/issue-credential/java/step2.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/issue-credential/java/step3.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/issue-credential/java/step4.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/issue-credential/java/template.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/negotiate-proof/java/NegotiateProof.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/java/RotateKey.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/java/step2.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/java/step3.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/java/step4.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/rotate-key/java/template.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/save-schema-and-cred-def/java/SaveSchemaAndCredDef.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/save-schema-and-cred-def/java/step2.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/save-schema-and-cred-def/java/step3.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/save-schema-and-cred-def/java/step4.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/save-schema-and-cred-def/java/template.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/java/WriteDIDAndQueryVerkey.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/java/step2.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/java/step3.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/java/step4.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/java/step5.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/write-did-and-query-verkey/java/template.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/how-tos/send-secure-msg/java/SendSecureMessage.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/java/src/main/java/Anoncreds.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/java/src/main/java/AnoncredsRevocation.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/java/src/main/java/Crypto.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/java/src/main/java/Endorser.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/java/src/main/java/Ledger.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/java/src/main/java/Main.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/java/src/main/java/utils/EnvironmentUtils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/java/src/main/java/utils/PoolUtils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/Callbacks.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ErrorCode.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/IOException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/IndyBool.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/IndyConstants.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/IndyException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/IndyJava.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/InvalidParameterException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/InvalidStateException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/InvalidStructureException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/LibIndy.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ParamGuard.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/StringUtils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/IndyIntegrationTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/IndyIntegrationTestWithPoolAndSingleWallet.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/IndyIntegrationTestWithSingleWallet.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/JsonObjectSimilar.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/ActionNotSupportedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/ErrorCode.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/InvalidParameterException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/LibVcx.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/NoAgentInfoException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/ParamGuard.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/StringUtils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/VcxConstants.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/VcxException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/VcxJava.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/ConnectionApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/CredentialApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/CredentialDefApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/DisclosedProofApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/ErrorCodeTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/ProofApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/SchemaApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/TestHelper.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/TokenApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/VcxApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/VcxExceptionTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/VcxUtilsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/test/java/com/evernym/sdk/vcx/WalletApiTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/Anoncreds.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/AnoncredsInvalidUserRevocId.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/AnoncredsJSONParameters.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/AnoncredsResults.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/CredDefAlreadyExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/CredentialRevokedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/CredentialsSearch.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/CredentialsSearchForProofReq.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/DuplicateMasterSecretNameException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/ProofRejectedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/anoncreds/RevocationRegistryFullException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/blob_storage/BlobStorageReader.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/blob_storage/BlobStorageWriter.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/cache/Cache.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/crypto/Crypto.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/crypto/CryptoJSONParameters.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/crypto/CryptoResults.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/crypto/UnknownCryptoException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/did/Did.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/did/DidAlreadyExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/did/DidJSONParameters.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/did/DidResults.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ledger/ConsensusException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ledger/Ledger.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ledger/LedgerInvalidTransactionException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ledger/LedgerJSONParameters.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ledger/LedgerResults.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ledger/LedgerSecurityException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/ledger/TimeoutException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/metrics/Metrics.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/non_secrets/WalletRecord.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/non_secrets/WalletSearch.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pairwise/Pairwise.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/ExtraFundsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/IncompatiblePaymentException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/InsufficientFundsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/PaymentOperationNotSupportedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/PaymentSourceDoesNotExistException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/Payments.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/PaymentsResults.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/TransactionNotAllowedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/payments/UnknownPaymentMethodException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/InvalidPoolException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/LedgerNotFoundException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/Pool.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/PoolConfigNotCreatedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/PoolIncompatibleProtocolVersionException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/PoolJSONParameters.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/PoolLedgerConfigExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/PoolLedgerTerminatedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/pool/PoolResults.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/DuplicateWalletTypeException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/InvalidWalletException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/UnknownWalletTypeException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/Wallet.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletAccessFailedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletAlreadyOpenedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletDecodingException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletEncryptionException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletInputException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletInvalidQueryException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletItemAlreadyExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletItemNotFoundException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletJSONParameters.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletNotFoundException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletResults.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WalletStorageException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/main/java/org/hyperledger/indy/sdk/wallet/WrongWalletForPoolException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/AnoncredsIntegrationTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/IssuerCreateAndStoreCredentialDefinitionTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/IssuerCreateCredentialTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/IssuerRevokeCredentialTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/IssuerRotateCredentialDefinitionTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverCreateCredentialRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverCreateMasterSecretTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverCreateProofTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverDeleteCredentialTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverGetCredentialTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverGetCredentialsForProofRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverGetCredentialsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverSearchCredentialsForProofRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverSearchCredentialsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ProverStoreCredentialTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/ToUnqualifiedTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/anoncreds/VerifierVerifyProofTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/cache/CacheIntegrationTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/cache/CredDefCacheTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/cache/SchemaCacheTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/CreateKeyTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/CryptoAnonCryptTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/CryptoAnonDecryptTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/CryptoAuthCryptTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/CryptoAuthDecryptTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/CryptoSignTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/CryptoVerifyTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/GetKeyMetadataTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/PackUnpackMessageTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/crypto/SetKeyMetadataTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/demo/AnoncredsDemoTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/demo/CryptoDemoTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/demo/LedgerDemoTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/demo/ReplaceKeysDemoTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/AbbreviateVerkeyTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/CreateMyDidTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/GetDidMetadataTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/GetDidWithMetaTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/GetEndpointForDidTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/KeyForDidTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/KeyForLocalDidTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/ListDidsWithMetaTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/QualifyDidTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/ReplaceKeysApplyTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/ReplaceKeysStartTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/SetDidMetadataTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/SetEndpointForDidTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/did/StoreTheirDidTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/error/GetErrorTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/interaction/AnoncredsRevocationInteractionTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/interaction/AnoncredsVerifyProofAfterCredentialRevokeTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/AcceptanceMechanismRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/AppendAuthorAgreementAcceptanceToRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/AppendRequestEndorserTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/AttribRequestsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/AuthRuleRequestsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/AuthorAgreementRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/CredDefRequestsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/GetFrozenLedgersTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/GetResponseMetadata.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/GetRevocRegDefRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/GetTxnRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/GetValidatorInfoRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/LedgerIntegrationTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/MultiSignRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/NodeRequestsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/NymRequestsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/PoolConfigRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/PoolRestartRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/PoolUpgradeRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/RequestsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/RevocGetRegDeltaRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/RevocGetRegRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/RevocRegDefRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/RevocRegEntryRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/SchemaRequestsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/SignRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/ledger/SubmitActionTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/metrics/CollectMetricsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/AddRecordTagsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/AddRecordTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/DeleteRecordTagsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/DeleteRecordTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/GetRecordTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/NonSecretsIntegrationTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/SearchTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/UpdateRecordTagsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/non_secrets/UpdateRecordValueTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pairwise/CreatePairwiseTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pairwise/GetPairwiseTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pairwise/ListPairwiseTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pairwise/PairwiseExistsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pairwise/PairwiseIntegrationTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pairwise/SetPairwiseMetadataTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/AddRequestFeesTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/BuildGetPaymentSourcesRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/BuildGetPaymentSourcesWithFromRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/BuildGetTxnFeesRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/BuildMintRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/BuildPaymentRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/BuildSetTxnFeesRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/BuildVerifyPaymentRequestTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/CreatePaymentAddressTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/GetRequestInfoTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/ListPaymentAddressesTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/ParseGetPaymentSourcesResponseTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/ParseGetPaymentSourcesWithFromResponseTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/ParseGetTxnFeesResponseTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/ParsePaymentResponseTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/ParseResponseWithFeesTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/ParseVerifyPaymentResponseTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/PaymentIntegrationTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/PreparePaymentExtraWithAcceptanceDataTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/SignWithAddressTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/payment/VerifyWithAddressTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pool/ClosePoolTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pool/CreatePoolTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pool/DeletePoolTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pool/ListPoolsTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pool/OpenPoolTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pool/RefreshPoolTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/pool/SetProtocolVersionTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/utils/EnvironmentUtils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/utils/InitHelper.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/utils/PoolUtils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/utils/StorageUtils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/wallet/CloseWalletTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/wallet/CreateWalletTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/wallet/DeleteWalletTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/wallet/ExportWalletTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/wallet/GenerateWalletKeyTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/wallet/ImportWalletTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/java/src/test/java/org/hyperledger/indy/sdk/wallet/OpenWalletTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/connection/ConnectionApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/connection/ConnectionErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/connection/InvalidConnectionHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/connection/InvalidInviteDetailsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/BuildCredentialDefReqErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/CreateCredentialDefException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/CreateCredentialRequestErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/CredentialApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/CredentialDefAlreadyCreatedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/GetCredentialCreateMsgidResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialDefHandle.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialDefJsonException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialJsonException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidCredentialRequestException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credential/InvalidIssuerCredentialHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credentialDef/CredentialDefApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/credentialDef/CredentialDefPrepareForEndorserResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/issuer/IssuerApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/CreateProofErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/CreateProofMsgIdResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/DisclosedProofApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/FailedProofComplianceException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/GetProofResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidDisclosedProofHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidProofCredentialDataException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidProofException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidProofHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/InvalidSelfAttestedValueException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/proof/ProofApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/InvalidSchemaCreationException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/InvalidSchemaException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/InvalidSchemaSeqNoException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/InvalidSchemahandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/SchemaApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/schema/SchemaPrepareForEndorserResult.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/token/InsufficientTokenAmountException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/token/TokenApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/utils/InvalidConfigurationException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/utils/PostMsgFailureException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/utils/UtilsApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/AlreadyInitializedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/BigNumberErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/CreatePoolConfigException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/IndySubmitRequestErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidAttributeStructureException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidDIDException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidGenesisTxnPathException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidHTTPResponseException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidJsonException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidKeyDelegateException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidMasterSecretException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidMessagesException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidMsgPackException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidNonceException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidObjHandleException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidOptionException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidPredicateException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidUrlException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/InvalidVerkeyException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/NoEndpointException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/NoPoolOpenException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/NotBase58Exception.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/NotReadyException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/PoolLedgerConnectException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/SerializationErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/TimeoutLibindyErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/UnknownErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/UnknownLibindyErrorException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/vcx/VcxApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletAccessFailedException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletAleradyOpenException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletAlreadyExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletApi.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletCreationException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletItemAlreadyExistsException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/src/main/java/com/evernym/sdk/vcx/wallet/WalletItemNotFoundException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/samples/android/WrapperTest/app/src/androidTest/java/com/evernym/connectme/wrappertest/ExampleInstrumentedTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/samples/android/WrapperTest/app/src/main/java/com/evernym/connectme/wrappertest/MainActivity.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/samples/android/WrapperTest/app/src/test/java/com/evernym/connectme/wrappertest/ExampleUnitTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/demo-android/AliceDemo/app/src/androidTest/java/com/sktelecom/ston/demo/ExampleInstrumentedTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/demo-android/AliceDemo/app/src/main/java/com/sktelecom/ston/demo/MainActivity.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vcx/wrappers/java/demo-android/AliceDemo/app/src/test/java/com/sktelecom/ston/demo/ExampleUnitTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`Gemfile`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `pom.xml`
- `build.xml`
- `build.gradle`

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

### ✅ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Contains https://wiki.hyperledger.org/display/.*(SEC|HYP)/Defect[.+]Response (`SECURITY.md`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`Jenkinsfile.ci`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`libindy/tests`).

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

</details>

