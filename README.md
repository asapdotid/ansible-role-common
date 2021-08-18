# Common setup

This ansible role install common packages On Ubuntu, CentOS

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    apt_repositories: []

Add repository

    apt_pkg_install: []

Package install

    zsh_theme: fino

ZSH Theme

    common_user: false

If another user will setup

    common_username: vagrant

If `common user setup true` it will be use

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: asapdotid.common }

## License

MIT / BSD

## Author Information

[JogjaScript](https://jogjascript.com)

This role was created in 2021 by [Asapdotid](https://jogjanode.com/).
