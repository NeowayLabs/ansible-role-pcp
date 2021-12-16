ansible-role-pcp
=========

[![Build Status](https://travis-ci.org/NeowayLabs/ansible-role-pcp.svg?branch=master)](https://travis-ci.org/NeowayLabs/ansible-role-pcp)

Installs Performance-Copilot (PCP).

Requirements
------------

None.

Role Variables
--------------

Optional:

`pcp_version`: Performance-Copilot version, default `4.1.1-1`

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-role-pcp }

License
-------

MIT

Author Information
------------------

NeowayLabs
