# Summary

Ansible playbook to setup docker & docker-compose

# How to use

 ansible-playbook -i hosts docker_build.yml --ask-become-pass

 To use different user / ssh key

 ansible-playbook -i hosts -u <user> --private-key="<private-key>" docker_build.yml

# Pre-work

- ssh-copy-id <target_server>
- Modify ip address in hosts file

