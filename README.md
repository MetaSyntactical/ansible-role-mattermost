# Ansible Role: Mattermost

[![Build Status](https://travis-ci.org/metasyntactical/ansible-role-mattermost.svg?branch=master)](https://travis-ci.org/metasyntactical/ansible-role-mattermost)

Installs Mattermost on Ubuntu Linux servers.

[Mattermost](http://www.mattermost.org/) is an open source, self-hosted Slack-alternative.

As an alternative to proprietary SaaS messaging, Mattermost brings all your
team communication into one place, making it searchable and accessible
anywhere. 

## Requirements

Mattermost requires either a MySQL or a PostgreSQL Server to connect to.

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
