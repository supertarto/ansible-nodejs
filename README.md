# Ansible Nodejs
[![Build Status](https://travis-ci.com/supertarto/ansible-nodejs.svg?branch=master)](https://travis-ci.com/supertarto/ansible-nodejs)

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
