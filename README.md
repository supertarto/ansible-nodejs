# Ansible Nodejs
[![CI](https://github.com/supertarto/ansible-nodejs/workflows/ci.yml/badge.svg?event=push)](https://github.com/supertarto/ansible-nodejs/actions?query=workflow%3ACI)

A very simple role to install nodejs and NPM

## Requirements
None.

## Tested plateform
* Debian 11 (Bullseye)
* Debian 12 (Bookworm)

## Role variables
The nodejs Version
```yml
nodejs_version: "20.x"
```

## Examples
```yml
- hosts: somehost
  roles:
    - supertarto.nodejs
  vars:
    nodejs_version: "20.x"
```

## Installation
```
ansible-galaxy install supertarto.nodejs
```
## License
GPL V3.0
