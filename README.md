Ansible Docker
==============

Installs docker (v0.13.0), docker-machine and docker-compose

Requirements
------------

No requirements.

Role Variables
--------------

No variables

Dependencies
------------

I haven't tested it without using my role `tjcim.ansible-vagrant-box`

Example Playbook
----------------

    ---
    - hosts: docker
      roles:
        - {role: 'tjcim.ansible-docker', tags: 'docker'}

License
-------

BSD

Author Information
------------------

Not Found
