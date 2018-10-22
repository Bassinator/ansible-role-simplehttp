# Ansible Role: simplehttp

[![Build Status](https://travis-ci.com/Bassinator/ansible-role-simplehttp.svg?branch=master)](https://travis-ci.com/Bassinator/ansible-role-simplehttp)

Install and start a SimpleHTTPServer to server a directory via http.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    installation_os_user: vagrant
    installation_os_group: vagrant
    www_dir: '/home/{{ installation_os_user }}/www/'

## Dependencies

None.


## Example Playbook


    - hosts: raspberries
      roles:
         - { role: bassinator.simplehttp, installation_os_user: pi }

## License

GNU GPLv3

## Author Information
This role was created in 2018 by [Bastian Bukatz](https://bassinator.github.io).
