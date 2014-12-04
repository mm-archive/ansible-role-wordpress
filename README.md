# Ansible Role: wordpress

A role to setup wordpress

## Requirements

A git repository with site files

## Role Variables

## Dependencies
There are no role dependcies but the role does expect that the following applications and services are installed. It also assumes ubuntu conventions for config file layout.
- Nginx
- Php
- MySql/Mariadb
- wp-cli

## Example Playbook


    - hosts: servers
      roles:
         - MatthewMiller.wordpress

## License

MIT

## Author Information

