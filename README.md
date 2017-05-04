InnoHub Ansible : ruby-install [![Build Status](https://travis-ci.org/lloydk/ruby-install.svg?branch=master)](https://travis-ci.org/lloydk/ruby-install)
==========================================================================================================================================================================

Installs ruby-install.

Requirements
------------

Tested ONLY on Ubuntu 16.04 Xenial.

Role Variables
--------------

ruby_install_version : defaults to '0.6.1'

Dependencies
------------

None

Example Playbook
----------------

Example Playbook:

    - hosts: servers
      roles:
         - { role: innohub-ansible.ruby-install }

Example Role:

    dependencies:
      - { role: ruby_install }

License
-------

MIT
