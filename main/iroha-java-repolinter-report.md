# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 3 | 3 | 9 | 4 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
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

Doesn't contain https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).

### ❌ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Doesn't contain license (`README.md`).

### ❌ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `MAINTAINERS.md`
- `MAINTAINERS.rst`


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `client/src/main/java/jp/co/soramitsu/iroha/java/BlocksQuery.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/BlocksQueryBuilder.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/ErrorResponseException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/FieldValidator.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/IrohaAPI.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/Query.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/QueryAPI.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/QueryBuilder.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/Transaction.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/TransactionBuilder.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/TransactionStatusObserver.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/Utils.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/ValidationException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/test/java/jp/co/soramitsu/iroha/java/BatchExample.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/test/java/jp/co/soramitsu/iroha/java/Example1.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/test/java/jp/co/soramitsu/iroha/java/Example2.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/test/java/jp/co/soramitsu/iroha/java/Example3.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/IrohaContainer.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/PeerConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/crypto/Ed25519Sha2SignatureBuilder.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/crypto/Ed25519Sha3SignatureBuilder.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/crypto/SignatureBuilder.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/debug/Account.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/debug/LoggingTransactionStatusObserver.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/debug/TestTransactionStatusObserver.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/detail/BuildableAndSignable.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/detail/Const.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/detail/Hashable.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/detail/InlineTransactionStatusObserver.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/detail/ReducedHashable.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/detail/StreamObserverToEmitter.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/detail/TransactionStatusObserverFace.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/routers/CmdRouter.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/routers/TxStatusRouter.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/subscription/SubscriptionStrategy.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/subscription/WaitForTerminalStatus.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/subscription/WaitUntilCompleted.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/DeepCloner.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/GenesisBlockBuilder.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/IrohaConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/LoggerConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/LoggerPattern.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/PostgresConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/RuntimeIOException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/ToriiTlsConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/detail/Verbosity.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/network/IrohaNetwork.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testcontainers/src/main/java/jp/co/soramitsu/iroha/testcontainers/network/PeerDescriptor.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `client/src/main/java/jp/co/soramitsu/iroha/java/detail/router/Router.java`: The first 7 lines do not contain the pattern(s): Copyright, License.

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

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/ci.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`testcontainers`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`build.gradle`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=javascript"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=go"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

