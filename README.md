# [backports](#backports)

Enable backports on Debian

|GitHub|GitLab|Quality|Downloads|Version|
|------|------|-------|---------|-------|
|[![github](https://github.com/buluma/ansible-role-backports/workflows/Ansible%20Molecule/badge.svg)](https://github.com/buluma/ansible-role-backports/actions)|[![gitlab](https://gitlab.com/shadowwalker/ansible-role-backports/badges/master/pipeline.svg)](https://gitlab.com/shadowwalker/ansible-role-backports)|[![quality](https://img.shields.io/ansible/quality/62010)](https://galaxy.ansible.com/buluma/backports)|[![downloads](https://img.shields.io/ansible/role/d/62010)](https://galaxy.ansible.com/buluma/backports)|[![Version](https://img.shields.io/github/release/buluma/ansible-role-backports.svg)](https://github.com/buluma/ansible-role-backports/releases/)|

## [Example Playbook](#example-playbook)

This example is taken from [`molecule/default/converge.yml`](https://github.com/buluma/ansible-role-backports/blob/master/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yaml
---
- name: Converge
  hosts: all
  tasks:
    - name: "Include buluma.backports"
      include_role:
        name: "buluma.backports"
```

Also see a [full explanation and example](https://buluma.github.io/how-to-use-these-roles.html) on how to use these roles.

## [Role Variables](#role-variables)

The default values for the variables are set in [`defaults/main.yml`](https://github.com/buluma/ansible-role-backports/blob/master/defaults/main.yml):

```yaml
---
# defaults file for backports
```

## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/buluma/ansible-role-backports/blob/master/requirements.txt).


## [Context](#context)

This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://buluma.github.io/) for further information.

Here is an overview of related roles:
![dependencies](https://raw.githubusercontent.com/buluma/ansible-role-backports/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/buluma):

|container|tags|
|---------|----|
|[Debian](https://hub.docker.com/repository/docker/buluma/debian/general)|all|

The minimum version of Ansible required is 2.10, tests have been done to:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them in [GitHub](https://github.com/buluma/ansible-role-backports/issues)

## [License](#license)

[Apache-2.0](https://github.com/buluma/ansible-role-backports/blob/master/LICENSE).

## [Author Information](#author-information)

[buluma](https://buluma.github.io/)

Please consider [sponsoring me](https://github.com/sponsors/buluma).
