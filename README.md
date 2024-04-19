Microsoft Repository
====================

An Ansible role to add `Microsoft` repository on Linux distros and install packages from it.

Requirements
------------

- Supported version of Ansible: 2.9 and highter.
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

- `microsoft_repository_mirror_url` Mirror of `Microsoft` repository (default: `https://packages.microsoft.com`).
- `microsoft_repository_gpgkey_url` URL to `Microsoft's` GPG public key file (default: `https://packages.microsoft.com/keys/microsoft.asc`).
- `microsoft_repository_dirs_list` List of repository directories. See [repository structure](https://packages.microsoft.com/).

  Available values:
  - `name` prod (default)
  - `type` ommited by default (see the example with the 'azure-cli' install).

- `microsoft_repository_packages` List of packages you want to install (default: `[]`).

Dependencies
------------

None.

Example Playbook
----------------

- Add the `Microsoft Prod` repository:

  ```yaml
  ---
  - name: 'Setup Microsoft repository'
    hosts: all

    roles:
      - role: antmelekhin.microsoft_repository
  ```

- Add the `Microsoft Prod` repository and install `dotnet-sdk-3.1` and `powershell` packages:

  ```yaml
  ---
  - name: 'Setup Microsoft repository'
    hosts: all

    roles:
      - role: antmelekhin.microsoft_repository
        microsoft_repository_packages:
          - dotnet-sdk-3.1
          - powershell
  ```

- Add the `Microsoft Azure CLI` repository and install the azure-cli package:

  ```yaml
  ---
  - name: 'Setup Microsoft repository'
    hosts: all

    roles:
      - role: antmelekhin.microsoft_repository
        microsoft_repository_dirs_list:
          - name: azure-cli
            type: alternative
        microsoft_repository_packages:
          - azure-cli
  ```

License
-------

MIT

Author Information
------------------

Melekhin Anton.
