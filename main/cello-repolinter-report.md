# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 3 | 4 | 9 | 2 | 18 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [❌ `integrates-with-ci`](#user-content--integrates-with-ci)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Did not find a file matching the specified patterns. (`CONTRIBUTING.md`).

### ❌ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `circle.yml`
- `.circleci/config.yml`
- `ci/azure-pipelines.yml`
- `.ci/azure-pipelines.yml`
- `Jenkinsfile`
- `Jenkinsfile.ci`
- `Jenkinsfile.cd`
- `.github/workflows/*.yml`


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `src/dashboard/config/config.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/config/plugin.config.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/config/router.config.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/config/theme.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/lambda/api.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/mock/agent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/mock/node.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/mock/organization.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/mock/user.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/scripts/generateMock.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/scripts/getPrettierFiles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/scripts/lint-prettier.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/scripts/prettier.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/app.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/defaultSettings.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/global.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/service-worker.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/tests/run-tests.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/tests/setupTests.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/lambda/mock/matchMock.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/e2e/baseLayout.e2e.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/e2e/home.e2e.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/e2e/login.e2e.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/e2e/topMenu.e2e.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/e2e/userLayout.e2e.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/layouts/BasicLayout.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/layouts/BlankLayout.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/layouts/Footer.js`: The first 5 lines do not contain the pattern(s): License.
- `src/dashboard/src/layouts/Header.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/layouts/MenuContext.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/layouts/UserLayout.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/locales/zh-CN.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/models/global.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/models/login.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/models/menu.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/models/node.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/models/setting.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/models/user.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/pages/404.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Authorized.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/services/agent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/services/api.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/services/error.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/services/node.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/services/organization.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/services/user.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/utils/Authorized.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/utils/authority.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/utils/authority.test.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/utils/getPageTitle.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/utils/networks.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/utils/request.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/utils/utils.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/utils/utils.test.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Authorized/Authorized.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Authorized/AuthorizedRoute.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Authorized/CheckPermissions.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Authorized/CheckPermissions.test.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Authorized/PromiseRender.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Authorized/Secured.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Authorized/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Authorized/renderAuthorize.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Exception/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Exception/typeConfig.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/FooterToolbar/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/GlobalFooter/index.js`: The first 5 lines do not contain the pattern(s): License.
- `src/dashboard/src/components/GlobalHeader/RightContent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/GlobalHeader/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/HeaderDropdown/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/IconFont/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Login/LoginItem.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Login/LoginSubmit.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Login/LoginTab.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Login/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Login/loginContext.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/Login/map.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/PageHeaderWrapper/GridContent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/PageHeaderWrapper/breadcrumb.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/PageHeaderWrapper/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/PageLoading/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SelectLang/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SettingDrawer/BlockCheckbox.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SettingDrawer/ThemeColor.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SettingDrawer/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SiderMenu/BaseMenu.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SiderMenu/SiderMenu.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SiderMenu/SiderMenu.test.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SiderMenu/SiderMenuUtils.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/SiderMenu/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/StandardTable/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/TopNavHeader/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/_utils/pathTools.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/components/_utils/pathTools.test.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/component.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/exception.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/form.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/locales/en-US/globalHeader.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/login.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/menu.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/operatorAgent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/operatorNode.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/operatorOrganization.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/en-US/operatorUser.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/locales/en-US/pwa.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/component.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/exception.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/form.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/locales/zh-CN/globalHeader.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/login.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/menu.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/operatorAgent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/operatorNode.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/operatorOrganization.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/operatorUser.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/locales/zh-CN/pwa.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Exception/403.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Exception/404.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Exception/500.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Exception/TriggerException.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Agent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Organization.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/pages/Operator/Overview.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/UserManagement.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/pages/Overview/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/User/Login.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/locales/en-US/fabric/ca.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/locales/zh-CN/fabric/ca.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Exception/models/error.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Agent/Agent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Agent/newAgent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Node/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/dashboard/src/pages/Operator/models/agent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/models/organization.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Node/New/basicInfo.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Node/New/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Node/New/nodeInfo.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Node/New/Fabric/ca.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Node/New/Fabric/orderer.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `src/dashboard/src/pages/Operator/Node/New/Fabric/peer.js`: The first 5 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

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

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`tests`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!node_modules/**`).

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

