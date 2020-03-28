# ansible-role-docker

An [Ansible](https://www.ansible.com/) role that installs
[Docker CE](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/),
[Docker Compose](https://docs.docker.com/compose/) and
[Docker Registry](https://docs.docker.com/registry/) on Ubuntu.

## Variables

See [default values](./defaults/main.yml).

Name|Description
---|---
docker_registry_image|Official [registry image](https://hub.docker.com/_/registry/)
docker_registry_port|Port on host to which to bind
docker_registry_volume|Directory on host in which to store persistent files
