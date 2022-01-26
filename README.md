fallenpixel devstation
=========

An ansible role to automate the management of all devices. Currently this 
module only updates all installed packages.

Requirements
------------

Only ansible.builtin modules are used. 

Role Variables
--------------
- naughty_mode: "false"
  If set to true, will update all packages. This setting breaks idempotence.

Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: common
      roles:
         - { role: common, naughty_mode: "true" }

License
-------

BSD

Author Information
------------------

fallenpixel/Eric Lehmann
https://katyl.info
