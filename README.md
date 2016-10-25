tmux-tpm
=========

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-tmux-tpm.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-tmux-tpm)

Install [tmux-plugins/tpm](https://github.com/tmux-plugins/tpm).

Requirements
------------

* git
* [motemen/ghq](https://github.com/motemen/ghq)

Role Variables
--------------

* ghq_executable: The executable path of ghq command. The default is "ghq".

Dependencies
------------

* [suzuki-shunsuke.ghq-module](https://galaxy.ansible.com/suzuki-shunsuke/ghq-module/)

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.tmux-tpm
```

License
-------

MIT
