# ansible-role-domain-manager 🐑 #

[![GitHub Build Status](https://github.com/cisagov/ansible-role-domain-manager/workflows/build/badge.svg)](https://github.com/cisagov/ansible-role-domain-manager/actions)
[![Total alerts](https://img.shields.io/lgtm/alerts/g/cisagov/ansible-role-domain-manager.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/cisagov/ansible-role-domain-manager/alerts/)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/cisagov/ansible-role-domain-manager.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/cisagov/ansible-role-domain-manager/context:python)

This is a project to provision a Domain Manager server.
Setup: [GhostWriter wiki](https://ghostwriter.wiki/documentation/installation/first-server-run)

## Requirements ##

This role uses the `git` Ansible module.

## Role Variables ##

Look at [vars/main.yml](vars/main.yml) for variables that
need to be changed for your environment.

## Dependencies ##

None.

## Example Playbook ##

Here's how to use it in a playbook:

```yaml
- hosts: all
  become: yes
  become_method: sudo
  roles:
    - domain_manager
```

## Contributing ##

We welcome contributions!  Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for
details.

## License ##

This project is in the worldwide [public domain](LICENSE).

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain
dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.

## Author Information ##

Krysta Coble - <krystacoble@gmail.com>
