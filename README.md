# Ansible Supervisor

*This ansible role is created and maintained by [Media Pop](https://www.mediapop.co), a software consultancy. Hire us to resolve your DevOps challenges.*

[![Travis](https://travis-ci.org/mediapop/ansible-python.svg?branch=master)](https://travis-ci.org/mediapop/ansible-python)

Install supervisor with superlance. On Ubuntu 16.04 it will also setup Python 2.7 until the next 4.x release that
brings python3 support.

## Example Playbook

```yml
- hosts: all
  roles:
    - role: mediapop.supervisor
```
