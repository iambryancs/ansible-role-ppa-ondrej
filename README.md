# Ansible Role: ondrej/php PPA

[![Build Status](https://travis-ci.org/iambryancs/ansible-role-ppa-ondrej.svg?branch=master)](https://travis-ci.org/iambryancs/ansible-role-ppa-ondrej)

Installs [ondrej/php](https://launchpad.net/~ondrej/+archive/ubuntu/php) ppa for Debian/Ubuntu

## Requirements
Make sure you are running this on Debian/Ubuntu host

## Dependencies
- none

## How to use
* Include `iambryancs.ppa-ondrej` in your requirements.yml
```yml
#requirements.yml
---
- src: iambryancs.ppa-ondrej
```
* Install the role by running `ansible-galaxy install -r path/to/your/requirements.yml`

## Example Playbook
```yml
- hosts: all
  roles: 
    - iambryancs.ppa-ondrej
```
## License
MIT
