# ansible-role-docker

## Requirements
- Ubuntu 18.04 LTS
- CentOS 8 / RHEL 8

## Installation

Define in requirements.yml
```
- src: https://github.com/ig33kmor3/ansible-role-docker
  version: master
  name: docker
```

Add to project:
```
ansible-galaxy install --roles-path path -r requirements.yml -f
```
