# Ansible Role: ONLYOFFICE Desktop Editors

[![Build Status](https://travis-ci.org/ONLYOFFICE/ansible-role-desktopeditors.svg?branch=master)](https://travis-ci.org/ONLYOFFICE/ansible-role-desktopeditors)

## Overview

**Ansible Role** is a set of tasks to configure a host to serve a certain purpose like configuring a service.
A role structure contains such directories as defaults, vars, tasks, files, templates, meta, handlers.
Ansible Role has to be used within **Playbook** that serves as a mapping between hosts and roles.

This Ansible Role installs and configures an open-source office suite [ONLYOFFICE Desktop Editors](https://github.com/ONLYOFFICE/DesktopEditors) on RHEL/CentOS or Debian/Ubuntu servers.

This Ansible Role is avaiable on [Ansible Galaxy](https://galaxy.ansible.com/ONLYOFFICE/desktopeditors), a repository for Ansible Roles that are available to drop directly into your Playbooks to streamline your automation projects.  

## Example Playbook

    - hosts: desktopeditors
      roles:
        - role: ONLYOFFICE.desktopeditors
          become: yes

## Dependencies

    None.

## License

GNU AGPL v3.0

## Author Information

This role was created by [ONLYOFFICE](https://www.onlyoffice.com/).
