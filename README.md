# Ansible Role: docker-swarm

[![Build Status](https://travis-ci.org/jonathonball/ansible-role-docker-swarm.svg?branch=master)](https://travis-ci.org/jonathonball/ansible-role-docker-swarm)

Configures hosts to be a docker swarm

## Requirements

Currently only supports the Ubuntu platform

Swarm manager must be in an ansible group titled `docker_swarm_manager`.

Swarm workers must be in an ansible group titled `docker_swarm_worker`.

## Role Variables

None

## Dependencies

 - jonathonball.docker

## Example Playbook

    - hosts: servers
      roles:
         - jonathonball.docker-swarm

## License

MIT

## Author Information

[Jon Ball](mailto:jonathon.ball@gmail.com)
