ansible-role-selenium
=====================

[![Build Status](https://travis-ci.org/arbouin-consulting/ansible-role-selenium.svg?branch=master)](https://travis-ci.org/arbouin-consulting/ansible-role-selenium)


Ansible Role - Selenium on Debian.

## Requirements

Java

## Role Variables

For Debian :

To change the list of packages to install:

    selenium:
      dir: /opt/selenium
      dir_log: /var/logs/selenium
      port: 4444
      driver:
        chrome_dir: /opt/chromedriver

## Example Playbook

    - hosts: selenium
      roles:
        - { role: lesmyrmidons.selenium }

## License

Apache version 2
