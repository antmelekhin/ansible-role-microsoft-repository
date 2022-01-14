Microsoft Repository
====================

Ansible роль для подключения репозитория `Microsoft` и установки из него пакетов.

Требования
----------

- Поддерживаемая версия Ansible: 2.7 и выше.
- Список поддерживаемых платформ описан в файле метаданных роли.

Используемые переменные
-----------------------

- `microsoft_repository__key_url` Файл публичного GPG ключа (default: `https://packages.microsoft.com/keys/microsoft.asc`).
- `microsoft_repository__packages` Список пакетов для установки из репозитория `Microsoft` (default: `[]`).

В файлах `vars\*.yml` находится переменная `microsoft_repository__url` с актуальной ссылкой для каждого дистрибутива.

Зависимости
-----------

Отсутствуют.

Пример использования
--------------------

- Подключаем репозиторий `Microsoft`:

  ```yaml
  ---

  - name: 'Setup Microsoft repository'
    hosts: all

    roles:
      - role: ansible-role-microsoft-repository
  ```

- Подключаем репозиторий `Microsoft` и устанавливаем пакет SDK версии 3.1 и Powershell:

  ```yaml
  ---

  - name: 'Setup Microsoft repository'
    hosts: all

    roles:
      - role: ansible-role-microsoft-repository
        microsoft_repository__packages:
          - dotnet-sdk-3.1
          - powershell
  ```

Лицензия
--------

MIT

Информация об авторе
--------------------

Мелехин Антон, ООО "ЖИЛИЩНАЯ ЭКОСИСТЕМА ВТБ".
