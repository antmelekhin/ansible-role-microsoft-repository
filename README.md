Microsoft Repository
====================

An Ansible role for add `Microsoft` repository on Linux distros and install packages from it.

Requirements
------------

- Supported version of Ansible: 2.9 and highter.
- List of all supported platforms described in role meta.

Role Variables
--------------

- `microsoft_repository_url` URL to `Microsoft` repository (default: define in `vars/*.yml`).
- `microsoft_repository_key_url` URL to `Microsoft's` GPG public key file (default: `https://packages.microsoft.com/keys/microsoft.asc`).
- `microsoft_repository_packages` List of packages you want to install (default: `[]`).

Dependencies
------------

None.

Example Playbook
----------------

- Add `Microsoft` repository:

  ```yaml
  ---

  - name: 'Setup Microsoft repository'
    hosts: all

    roles:
      - role: ansible-role-microsoft-repository
  ```

- Add `Microsoft` repository, install SDK 3.1 and Powershell:

  ```yaml
  ---

  - name: 'Setup Microsoft repository'
    hosts: all

    roles:
      - role: ansible-role-microsoft-repository
        microsoft_repository_packages:
          - dotnet-sdk-3.1
          - powershell
  ```

License
-------

MIT

Author Information
------------------

Melekhin Anton.
