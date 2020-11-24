# Ansible Nodejs
[![CI](https://github.com/supertarto/ansible-nodejs/workflows/CI/badge.svg?event=push)](https://github.com/supertarto/ansible-nodejs/actions?query=workflow%3ACI)

A very simple role to install nodejs and NPM

## Requirements
None.

## Tested plateform
* Debian 10 (Buster)

## Role variables
The nodejs Version
```yml
nodejs_version: "12.x"
```

## Examples
```yml
- hosts: somehost
  roles:
    - supertarto.nodejs
  vars:
    nodejs_version: "12.x"
```

## Installation
```
ansible-galaxy install supertarto.nodejs
```
## License
GPL V3.0
