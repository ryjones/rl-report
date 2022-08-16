# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 3 | 8 | 8 | 0 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
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
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)

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

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `wrappers/javascript/nodejs/babel.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/babel.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/demo/demo.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/demo/logger.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/errors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/rustlib.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/tools.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/vdr.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/module-resolver-helper.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/NodeJSIndyVdr.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/error.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/AcceptanceMechanismsRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/AttribRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/CredentialDefinitionRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/CustomRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/DisableAllTransactionAuthorAgreementsRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetAcceptanceMechanismsRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetAttribRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetCredentialDefinitionRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetNymRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetRevocationRegistryDefinitionRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetRevocationRegistryDeltaRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetRevocationRegistryRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetRichSchemaObjectByIdRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetRichSchemaObjectByMetadataRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetSchemaRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetTransactionAuthorAgreementRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetTransactionRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/GetValidatorInfoRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/IndyVdrPool.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/IndyVdrRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/NymRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/RevocationRegistryDefinitionRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/RevocationRegistryEntryRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/RichSchemaRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/SchemaRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/TransactionAuthorAgreementRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/ReactNativeIndyVdr.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/error.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/common.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/ffi-tools.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/indy-vdr-pool.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/indy-vdr-utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/utils/error-message.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/utils/ffi-helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/utils/memory-management-helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/common/init.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/integration/main.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/unit/ffi-tools.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/unit/indy-vdr-pool.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/unit/indy-vdr-utils.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/alloc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/callback.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/conversion.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/primitives.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/serialize.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/structures.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/library/NativeBindings.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/library/bindings.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/library/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/library/register.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/utils/fixtures.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/utils/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/utils/initialize.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/library/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/library/register.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/utils/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/utils/serialize.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/AcceptanceMechanismsRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/AttribRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/CredentialDefinitionRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/CustomRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/DisableAllTransactionAuthorAgreementsRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetAcceptanceMechanismsRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetAttribRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetCredentialDefinitionRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetNymRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetRevocationRegistryDefinitionRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetRevocationRegistryDeltaRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetRevocationRegistryRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetRichSchemaObjectByIdRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetRichSchemaObjectByMetadataRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetSchemaRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetTransactionAuthorAgreementRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetTransactionRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/GetValidatorInfoRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/NymRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/PoolCreate.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/RevocationRegistryDefinitionRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/RevocationRegistryEntryRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/RichSchemaRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/SchemaRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/TransactionAuthorAgreementRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/builder/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/indyVdr/IndyVdrNativeBindings.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/indyVdr/IndyVdrPool.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/indyVdr/IndyVdrRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/indyVdr/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/indyVdr/indyVdr.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/types/IndyVdr.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/types/Utility.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/types/builderTypes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/types/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/types/types.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/ledger-requests/ledger-request-custom.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/ledger-requests/ledger-request-get-nym.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/ledger-requests/ledger-request-get-schema.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/ledger-requests/ledger-request-get-txn.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/ledger-requests/ledger-request-get-validator-info.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/ledger-requests/ledger-request-nym.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/src/api/ledger-requests/ledger-request.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/unit/ledger-requests/ledger-request-custom.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/nodejs/test/unit/ledger-requests/ledger-request-get-txn.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/crypto/edsigner.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/identifiers/did.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/identifiers/did_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/claim_def.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/claim_def_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/doc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/model.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/reply.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/requests.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/schema.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/schema_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/signature.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/signature_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/sortedmap.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/sortedmap_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/vdr/writes.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/golang/cmd/demo/demo.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/android/src/main/java/org/hyperledger/indyvdr/IndyVdrModule.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/android/src/main/java/org/hyperledger/indyvdr/IndyVdrPackage.java`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`go.mod`).

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

Found file (`.github/workflows/build.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`docker/test-python.sh`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

