[![Build Status](https://travis-ci.com/calvinbui/ansible-calibre_web-docker.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-calibre_web-docker)
![GitHub release](https://img.shields.io/github/release/calvinbui/ansible-calibre_web-docker.svg)
![Ansible Quality Score](https://img.shields.io/ansible/quality/42298.svg)
![Ansible Role](https://img.shields.io/ansible/role/d/42298.svg)

# Ansible Calibre Web

Calibre Web in Docker

##  Requirements

N/A

## Role Variables

`calibre_web_name`: Name of container

`calibre_web_image`: Docker image to  use

`calibre_web_ports`: List of ports to expose

`calibre_web_config_directory`: Directory to store configuration files

`calibre_web_books_directory`: Directory to store books

`calibre_web_environment_variables`: Docker environmental variables

`calibre_web_docker_additional_options`: [Additional parameters](https://docs.ansible.com/ansible/latest/modules/docker_container_module.html) to add to docker container

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
   - role: calvinbui.ansible_calibre_web_docker
```

## License

GPLv3

## Author Information

http://calvin.me
