# Ansible Role: Ruby

[![CI][badge-gh-actions]][link-gh-actions]

Installs ruby and global ruby gems.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    ruby_versions: []

Ruby versions you would like to make sure are installed with rbenv.

    ruby_global_gems: []

Global Ruby gems you would like to make sure are installed.

## Dependencies

  - [kadaan.homebrew](https://galaxy.ansible.com/kadaan/homebrew/)

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.ruby, ruby_execute: true }

## License

Apache 2.0

[badge-gh-actions]: https://github.com/kadaan/ansible-role-ruby/workflows/CI/badge.svg?event=push
[link-gh-actions]: https://github.com/kadaan/ansible-role-ruby/actions?query=workflow%3ACI
