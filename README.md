osx-vim
=======

An Ansible role to setup vim on OS X

Requirements
------------

[Homebrew](http://brew.sh/) must be installed.

Role Variables
--------------

None.

Dependencies
------------

- hnakamur.oh-my-zsh
- hnakamur.osx-go

Example Playbook
----------------

    - hosts: servers
      roles:
         - hnakamur.osx-vim

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
