# Ansible Role: Mattermost

[![Build Status](https://travis-ci.org/MetaSyntactical/ansible-role-mattermost.svg?branch=master)](https://travis-ci.org/MetaSyntactical/ansible-role-mattermost)

Installs Mattermost on Ubuntu Linux servers.

## What is Mattermost?

[Mattermost](http://www.mattermost.org/) is an open source, self-hosted Slack-alternative.

As an alternative to proprietary SaaS messaging, Mattermost brings all your
team communication into one place, making it searchable and accessible
anywhere. 

## Requirements

Mattermost requires either a MySQL or a PostgreSQL Server to connect to.

A suitable Ansible role for installing a PostgreSQL Server as backend may be
[ANXS.postgresql](https://galaxy.ansible.com/ANXS/postgresql/).

The role requires installed monit if you request to install monit protection
with variable ```monit_protection: yes ```. A suitable ansible role for
installing monit may be [ANXS.monit](https://galaxy.ansible.com/ANXS/monit/).

## Role Variables

(tbd.)

## Dependencies

None.

## Example Playbook

    - hosts: appserver
      sudo: yes
      roles:
        - { role: metasyntactical.mattermost }

## License

MIT

## Author Information

This role was created in 2016 by [Daniel Kreuer](http://danielkreuer.com/) as part of [MetaSyntactical](http://metasyntactical.com/).
