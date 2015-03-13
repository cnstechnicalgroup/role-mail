Role: cns.postfix
========

This role installs and configures postfix.

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

In the current version, you can specify the following variables:

| Name               | Default |                                      |
|--------------------|---------|--------------------------------------|
| ---                |   ---   | ---                                  |


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
    - cns.postfix
```
