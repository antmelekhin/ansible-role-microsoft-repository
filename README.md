Microsoft Repository
====================

An Ansible role that adds the [Microsoft repository](https://packages.microsoft.com) to Linux distributions and installs packages from it.

Upgrade to 2.x
--------------

Since version 2.0.0, the variable `microsoft_repository_dirs_list` has changed to `microsoft_repository_enable_prod_repository` and `microsoft_repository_additional_directories`.

Requirements
------------

- Supported version of Ansible: 2.12 and highter.
- Supported platforms:
  - Debian
    - 10
    - 11
  - RHEL
    - 7
    - 8
    - 9
  - Ubuntu
    - 18.04
    - 20.04
    - 22.04

Role Variables
--------------

All variables that can be overridden are stored in the [defaults/main.yml](https://github.com/antmelekhin/ansible-role-microsoft-repository/blob/main/defaults/main.yml) file.
Please refer to the [meta/argument_specs.yml](https://github.com/antmelekhin/ansible-role-microsoft-repository/blob/main/meta/argument_specs.yml) file for a description of the available variables.
Similarly, descriptions and defaults for preset variables can be found in the [vars/main.yml](https://github.com/antmelekhin/ansible-role-microsoft-repository/blob/main/vars/main.yml) file.

Dependencies
------------

None.

Example Playbook
----------------

Add the `Microsoft Prod` repository:

```yaml
---
- name: 'Setup Microsoft repository'
  hosts: all

  roles:
    - role: antmelekhin.microsoft_repository
```

Add the `Microsoft Prod` repository and install `dotnet-sdk-3.1` and `powershell` packages:

```yaml
---
- name: 'Setup Microsoft repository'
  hosts: all

  roles:
    - role: antmelekhin.microsoft_repository
      microsoft_repository_packages:
        - 'dotnet-sdk-3.1'
        - 'powershell'
```

Add the `Microsoft Azure CLI` repository and install the azure-cli package:

```yaml
---
- name: 'Setup Microsoft repository'
  hosts: all

  roles:
    - role: antmelekhin.microsoft_repository
      microsoft_repository_additional_directories:
        - 'azure-cli'
      microsoft_repository_packages:
        - 'azure-cli'
```

License
-------

MIT

Author Information
------------------

Melekhin Anton.
