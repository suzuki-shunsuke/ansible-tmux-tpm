# ansible-tmux-tpm

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-tmux-tpm.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-tmux-tpm)

ansible role to install [tmux-plugins/tpm](https://github.com/tmux-plugins/tpm).

## Requirements

* tmux
* git

## Role Variables

name | required | default | description
--- | --- | --- | ---
tmux_tpm_plugins_path | no | `{{ansible_env.HOME}}/.tmux/plugins` |
tmux_tpm_repo | no | https://github.com/tmux-plugins/tpm |
tmux_tpm_version | no | HEAD |

## Dependencies

Nothing.

## Example Playbook

```yaml
- hosts: servers
  roles:
    - suzuki-shunsuke.tmux-tpm
```

## License

[MIT](LICENSE)
