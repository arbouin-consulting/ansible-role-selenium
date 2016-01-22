ansible-role-selenium
=====================

[![Build Status](https://travis-ci.org/lesmyrmidons/ansible-role-selenium.svg?branch=master)](https://travis-ci.org/lesmyrmidons/ansible-role-selenium)

Ansible Role - Selenium on Debian.

## Requirements

Java

## Role Variables

For Debian :

To change the list of packages to install:

	docker_packages:
	  - docker.io

## Example Playbook

    - hosts: docker
      roles:
        - { role: lesmyrmidons.docker }

## License

Apache version 2
