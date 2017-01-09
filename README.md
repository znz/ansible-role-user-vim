# Ansible role to enable vim-addons of user

- enable vim-editorconfig

## Requirements

- Debian
- Ubuntu

## Role Variables

None.

## Dependencies

- [vim-editorconfig](http://packages.debian.org/vim-editorconfig)

## Example Playbook

Normal usage:

    ---
    - hosts: all
      become: no
      roles:
      - znz.user-vim

## Example requirements.yml

    - src: https://github.com/znz/ansible-role-user-vim
      version: master
      name: znz.user-vim

## License

MIT License
