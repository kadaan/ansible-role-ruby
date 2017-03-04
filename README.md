# Ansible Role: Ruby

[![Build Status](https://travis-ci.org/kadaan/ansible-role-ruby.svg?branch=master)](https://travis-ci.org/kadaan/ansible-role-ruby)

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

  - `kadaan.homebrew`

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.ruby }

## License

Apache 2.0
