[![Build
Status](https://travis-ci.org/wtanaka/ansible-role-docker.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-docker)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-docker.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-docker)

wtanaka.docker
==============

Ansible role to install docker on ubuntu

Example Playbook
----------------

    - hosts: all
      roles:
        - { role: wtanaka.docker, docker_users: ['myusername'] }


Author Information
------------------

http://wtanaka.com/
