<img style="float:left" alight="left" height="128px" width="128px" src="https://github.com/iaroslavb/ansible-role-fail2ban/raw/master/fail2ban_logo.png">

Ansible Role: Fail2ban
=========

[![Build Status](https://img.shields.io/travis/iaroslavb/ansible-role-fail2ban/master.svg?style=for-the-badge)](https://travis-ci.org/iaroslavb/ansible-role-fail2ban)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)](https://raw.githubusercontent.com/iaroslavb/ansible-role-fail2ban/master/LICENSE)

Ansible role for installing and configuring fail2ban service on Ubuntu Linux

Requirements
------------

None

Role Variables
--------------
```
ssh_bantime - ban time for sshd service
```

Dependencies
------------

None


Example Playbook
----------------

TODO

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Created by Yaroslav Bannov
