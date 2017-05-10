Ansible-my-shell
================

This repository contains an ansible role to setup my *nix shell environment,
by pulling my dotfiles from source control (github).

Variables
---------
is_server: True or false
- If True, a symbolic link will be created to bash_profile_server.  This will not attempt to load an SSH key into memory.
- If False, a symblic link will be created to bash_profile.  This will attempt to load your primary SSH key into memory.

Note: My dotfiles repostiory will use keychain or ssh-agent to host SSH keys.

License
-------
MIT

Author
------
Glenn H. Snead
glennsnead@gmail.com

