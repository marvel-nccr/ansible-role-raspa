[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-raspa.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-raspa)

# Ansible Role: marvel-nccr.raspa

An ansible role that installs [RASPA2](https://github.com/iRASPA/RASPA2.git) on Ubuntu.

## Installation

`ansible-galaxy install marvel-nccr.raspa`

## Role Variables

See `defaults/main.yml`

Note: By default, this role checks out RASPA from a private git repository and
you will need to provide an SSH deploy key to access it.

## Example Playbook

  - hosts: servers
    roles:
    - role: marvel-nccr.raspa

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
