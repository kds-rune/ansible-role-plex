ruro.plex
=========

  plex: A simple role to install plex media server from plex repository.

  After installation, you can access the server from the following URL to configure:

    - https://<hostname>:32400/web

  Files in use:
    - tasks/main.yml
      - imports: install-RedHat.yml
      - imports: firewall-RedHat.yml
      - imports: services.yml
    - handlers/main.yml

Requirements
------------

  None

Role Variables
--------------

  None

Dependencies
------------
  None

Example Playbook
----------------

  - hosts: localhost
    roles:
       - { role: noruro.plex }

License
-------

  MIT

Author Information
------------------

  N/A
