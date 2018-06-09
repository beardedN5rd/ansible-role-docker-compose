# Ansible Role: ansible-role-docker-compose

An *ansible role* that installs [Docker Compose](https://docs.docker.com/compose/) on Linux.

## Requirements

[Ansible](https://www.ansible.com/)

## Configuration

The role may be configured by changing the following variables.

    docker_compose_version: "1.21.2"
    docker_compose_destination_path: /usr/local/bin/docker-compose

Please see the [release notes](https://docs.docker.com/release-notes/docker-compose/) to choose the correct compose version for your docker engine version.

## License

MIT
