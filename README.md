Role Name
=========
Neovim

Requirements
------------
Package manager for either/or python, nodejs and ruby need to be available when using `with_support_for`.

Role Variables
--------------
```
with_support_for: []
```
Possible values for the list are ['nodejs', 'python', 'ruby']

Example Playbook
----------------

    - hosts: localhost
      connection: local
      roles:
         - { role: ck3mp3r.neovim, with_support_for: ['nodejs'] }

License
-------

MIT

Author Information
------------------

Christian Kemper | kemper.buzz
