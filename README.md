# Ansible role: ansible_role_docker
[![CI](https://github.com/origox/ansible_role_docker/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/origox/ansible_role_docker/actions/workflows/ci.yml)

An Ansible role that install and configure docker

## Development and local test of new role
```bash
# Setup virtual environment
$ python3 -m pip install venv
$ source venv/bin/activate
$ python3 -m pip install -r requirements.txt

# YAML Lint
$ yamllint .

# Ansible lint
$ ansible-lint

# Molecule
$ molecule test
```

## Requirements

None.

## Role Default Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

None

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - role: 
            src: https://github.com/origox/ansible_role_docker 
