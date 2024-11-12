Install Lighthouse for Clickhouse over Nginx
============================================

Роль скачивает файлы Lighthouse и раздает их через Nginx

Requirements
------------

Роль должна проигрываться от пользователя с правами sudo

Роль проигрывается на платформах, указанных в meta

Role Variables
--------------

Дополнительные переменные отсутствуют

Dependencies
------------

Для работы Lighthouse требуется веб-сервер.

В качестве веб-сервера используется NGINX.

В зависимостях указана роль установки NGINX.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: lighthouse
      roles:
         - lighthouse

License
-------

MIT
