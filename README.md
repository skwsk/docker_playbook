# Summary

Ansible playbook to setup docker & docker-compose
- capture latest version of docker-compose
- download docker-compose only if required

# How to use

 ansible-playbook -i hosts docker_build.yml --ask-become-pass

# Pre-work

- ssh-copy-id <target_server>
- Modify ip address in hosts file

