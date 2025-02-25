# Changelog

## [2.0.1](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v2.0.0...v2.0.1) (2024-12-07)


### Documentation

* **README:** updated requirements ([7c9e891](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/7c9e89172474102bc52aaca56f8b4addde0df503))

## [2.0.0](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.5.1...v2.0.0) (2024-09-13)


### ⚠ BREAKING CHANGES

* update variables (#19)

### Improvements

* update variables ([#19](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/19)) ([37d493a](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/37d493a62dc18bac8351745448234f576ff7a687))

## [1.5.1](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.5.0...v1.5.1) (2024-09-07)


### Documentation

* **README:** update variables description ([59e89c4](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/59e89c4fa331b4c30d860cee935ccd1a185c119f))

## [1.5.0](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.4.0...v1.5.0) (2024-09-04)


### Features

* add `meta/argument_specs.yml` file ([#18](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/18)) ([5665283](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/5665283482296cef068377a4c522143804fee083))

## [1.4.0](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.3.4...v1.4.0) (2024-09-04)


### Improvements

* merge OS-specific variables into the `vars/main.yml` file ([#17](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/17)) ([17a6f31](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/17a6f31e2b63166e1f31329f94696a95d87ca1a1))


### Styles

* update common role style ([#16](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/16)) ([b6a964d](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/b6a964df04e60955fe0b2326270c2e5c0c5fb1c6))

## [1.3.4](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.3.3...v1.3.4) (2024-05-13)


### Documentation

* **README:** update variables documentation ([8a9bc5b](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/8a9bc5b69cec33f154f95d3638c2305308ed4aa0))


### Fixes

* fix task and molecule instance names ([d52d156](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/d52d156a1852b4181f85a3012d60abf9b51997d8))


### Styles

* rename tasks ([6cf9a99](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/6cf9a99331135450c97d59646dac49f3edb098d0))

## [1.3.3](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.3.2...v1.3.3) (2024-04-27)


### Documentation

* **README:** fixed examples view for Ansible Galaxy ([e3a9099](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/e3a9099de2d08a53eb6684ce49dfe89b3eb36c48))


### Fixes

* fixed running a role in check_mode ([fd3a155](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/fd3a155671542e570048cbd4350c9ca9e44ec24a))


### Styles

* add newline to end of file ([24f476c](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/24f476c1dcb90470402127021cfd6a988a75980d))
* use double underline register variable and quote strings ([9554d91](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/9554d91b12eb8f1873664744ace086b5eda3ceba))


### Tests

* add .tox as ignore ([0d60da4](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/0d60da46a5d91e84baa0d69088c0f786b45e1903))
* add role_name prefix to instance name ([222ee5d](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/222ee5d8885f979d6da7a29acf4287323d50b0b7))
* run linters in its own workflow ([853ffc5](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/853ffc5586d0fab6434ba5831dc1764700d2bdf4))

## [1.3.2](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.3.1...v1.3.2) (2024-04-19)


### Code Refactoring

* update variable names, quote strings and rm loop for include_vars ([#15](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/15)) ([c7c209c](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/c7c209c0f6c14acf05a3939f8646ebfb995f3531))

## [1.3.1](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.3.0...v1.3.1) (2024-04-17)


### Continuous Integration

* update release rules ([56e97e1](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/56e97e148bdae2caabffa153a2175bfc9ba52157))
* update workflows ([de1bc91](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/de1bc910f730b4d881f706ffe798ba03473cd574))


### Documentation

* **README:** update supported platforms in README and meta ([8f7af45](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/8f7af4590f2048aa37478d88571d284434a3f593))


### Styles

* add `_microsoft_repository_local_gpgkey` variable and merge debian/ubuntu vars files ([#14](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/14)) ([f3b74a5](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/f3b74a5a55a19ede48e50a27362dc4515dad2034))

## [1.3.0](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.2.6...v1.3.0) (2024-03-10)


### Continuous Integration

* fix publish workflow ([ea64756](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/ea64756c19d98cc82f3470ac7d5b501f6609cf87))


### Improvements

* update variable names and add other changes ([#12](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/12)) ([21cad76](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/21cad7680b4dab1417df6beed10a6ccb3ca0a8c4))


### Styles

* minor fixes ([#13](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/13)) ([f0261e7](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/f0261e7d50e3b97ff862825e38fbec485cb8472c))
* revert empty line after ansible comment ([860d44b](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/860d44b4fd72d36e74df11694798f56c249ae3a6))

## [1.2.6](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.2.5...v1.2.6) (2023-09-13)


### Fixes

* add missing arch in apt repo list ([#10](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/10)) ([1acdf90](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/1acdf903a7f56d102643336f77857997c7b739e0))

## [1.2.5](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.2.4...v1.2.5) (2023-08-24)

### Fixes

* add `update_cahce` in debian task for fix idempotence ([18f3f26](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/18f3f26829469f8bf1d4e9ff4c779f426f53ee62))

### Tests

* add tox ([0e5809c](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/0e5809c7d70aabadbd35518d041ada2b79d9bbce))

## [1.2.4](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.2.3...v1.2.4) (2023-07-24)

### Fixes

* update `_microsoft_repository_baseurl` variable for Debian ([6d034fa](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/6d034faec7914eacb11e8ec176657f1bb03e13aa))

## [1.2.3](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.2.2...v1.2.3) (2023-07-24)

### Continuous Integration

* add release type `improv` ([9a0137a](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/9a0137a55fe71081d2d87c518a3e59c7669aa59c))
* rm `tagFormat` option, update `commit-analyzer` and `release-notes-generator` blocks ([9e9319b](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/9e9319bc96486ccb6ce3d4e7d54205adafd45a01))

### Fixes

* change `*_repository` modules to `template` in `Add Microsoft Repository` tasks ([0b166b6](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/0b166b6a782e09aa3686985398cb34ea45fee047))

## [1.2.2](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/1.2.1...1.2.2) (2023-06-14)

### Fixes

* **test:** replace `shell` to `command` module in verify step ([6cc16a4](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/6cc16a425c6c8822b1d8c5d362c60a140f924532))

## [1.2.1](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.2.0...1.2.1) (2023-06-14)

### Fixes

* improve the task key order ([7950372](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/79503723f9d59f26c5eb5e8d1769c2432ce10f42))

### Tests

* update `molecule` scenario and workflow ([2d0d361](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/2d0d3613092305b2af21bb98a999caa58f13a7a9))

# [1.2.0](https://github.com/antmelekhin/ansible-role-microsoft-repository/compare/v1.1.1...v1.2.0) (2023-04-30)

### Features

* add ability to select dirs of the repository ([#6](https://github.com/antmelekhin/ansible-role-microsoft-repository/issues/6)) ([d3bd7a6](https://github.com/antmelekhin/ansible-role-microsoft-repository/commit/d3bd7a6d5d8156bd14a0be97d04e72f8f7bdb9b2))
