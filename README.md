About
-----

Ansible role for install jekyll on Debian/Ubuntu.

Note:
You must [install rvm](https://galaxy.ansible.com/list#/roles/1087) before.

Installation
------------

```bash
ansible-galaxy install igor_mukhin.jekyll
```

Usage
-----

```yml
vars:
  jekyll_version: 2.5.3

roles:
  - {role: igor_mukhin.jekyll, tags: jekyll }
```
