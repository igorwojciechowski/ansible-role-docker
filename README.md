# ansible-role-docker

Ansible role for installing and configuring docker service

## Tasks

* Install docker
* Create directory for docker files
* Add user to `docker` group
* Copy `docker.service` to `/lib/systemd/system/` directory
    * Configured to expose docker API on port `2375`
