Role: cns.mail
========

This role sets system mailname and installs / configures postfix on Debian.

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

In the current version, you can specify the following variables:

| Name               | Default |                                      |
|--------------------|---------|--------------------------------------|
| mailname           |   ---   | The visible mail name of the system. |


Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

Created by [Sam Morrison](https://www.twitter.com/samcns)

Examples
--------

```yaml
---
- name: cns.postfix example
  hosts: all
  roles:
    - cns.mail
```
