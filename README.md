Neovim
=========

Install Neovim and manage it's dotfiles for multiple users.

Requirements
------------

Must have privilege to:
* install software on the host.
* be able to use `become_user` to manage a user's dotfiles.

Role Variables
--------------

The name of the package to install can be configured with `neovim_package`, it
defaults to `neovim`.

Dependencies
------------

This role has no dependencies.

Example Playbook
----------------

This role can be used without any additional values to simply install Neovim.

    - hosts: servers
      roles:
         - { role: vanjanssen.neovim }

License
-------

MIT

Author Information
------------------

Author: Erwin Janssen
