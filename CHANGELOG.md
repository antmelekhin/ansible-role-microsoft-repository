# Changelog

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
