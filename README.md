# ansible-apps_packer

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_packer-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_packer)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_packer.svg)](https://github.com/lotusnoir/ansible-apps_packer/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_packer?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_packer)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_packer)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_packer)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install hashicorp packer in order to create templates
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_packer
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_packer


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
