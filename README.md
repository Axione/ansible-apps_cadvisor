# ansible-apps_cadvisor

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_cadvisor-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_cadvisor)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_cadvisor.svg)](https://github.com/lotusnoir/ansible-apps_cadvisor/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_cadvisor?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_cadvisor)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_cadvisor)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_cadvisor)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Install and configure cadvisor for docker metrics.
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_cadvisor
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_cadvisor


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
