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
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
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

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`Jenkinsfile.ci`).

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

