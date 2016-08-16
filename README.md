Ansible role piwik-LoginLdap
============================

[![Build Status](https://travis-ci.org/nwoetzel/ansible-role-piwik-LoginLdap.svg?branch=master)](https://travis-ci.org/nwoetzel/ansible-role-piwik-LoginLdap)

This ansible role installs the LdapLogin plugin for a piwik installation. Optionally, it also configures given ldap servers into the config.ini.php

Requirements
------------

A piwik installation is required. For ldap functionality a php-ldap module will also be needed.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPLv3

Author Information
------------------

For information about this role, please see meta/main.yml
