# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 4 | 5 | 8 | 2 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
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
  - [✅ `readme-references-license`](#user-content--readme-references-license)
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

Doesn't contain https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

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

- `commitlint.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `metro.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/metro.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/babel.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/cli.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/jest.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/jestSetup.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/react-native.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/file.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/style.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/@react-native-async-storage/async-storage.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__tests__/util/timetravel.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `genesis-utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/declarations.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/constants.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/theme.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/react-i18next.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/react-native-argon2.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/react-native-keychain.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__tests__/helpers.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__tests__/luminance.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__tests__/testable.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/components/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/config/keychain.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/contexts/theme.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/hooks/notifications.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/localization/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/navigators/defaultStackOptions.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/services/kdf.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/services/keychain.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/types/decline.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/types/error.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/types/fn.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/types/navigators.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/types/react-i18next.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/types/record.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/types/security.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/types/state.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/utils/cred-def.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/utils/helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/utils/luminance.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/utils/schema.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/utils/testable.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/@aries-framework/react-hooks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/components/chat/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/contexts/reducers/store.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/localization/en/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/App/localization/fr/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/custom/@react-navigation/core.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/__mocks__/custom/@react-navigation/native.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/bcovrin-test/genesis-file.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/bcovrin-test/pool-config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/candy-dev/genesis-file.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/candy-dev/pool-config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/indicio-test-net/genesis-file.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/indicio-test-net/pool-config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/sovrin-builder-net/genesis-file.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/sovrin-builder-net/pool-config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/sovrin-main-net/genesis-file.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/sovrin-main-net/pool-config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/sovrin-staging-net/genesis-file.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/configs/ledgers/indy/sovrin-staging-net/pool-config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/android/app/src/main/java/com/ariesbifold/MainActivity.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `app/android/app/src/main/java/com/ariesbifold/MainApplication.java`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`Gemfile`).

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

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/quality.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`core/__tests__/testable.test.ts`).

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

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

