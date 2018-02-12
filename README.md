ho-ansible/R
=========

R statistical software

Requirements
------------

Only on Debian stable, for now.

Role Variables
--------------

+ `cran_key`: PGP key for verifying packages
+ `cran_mirror`: URL from which to download packages, see [mirror list](https://cran.r-project.org/mirrors.html)
+ `cran_ver`: R version, e.g., `cran34` for R v3.4.x

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: R
  roles:
    - { role: ho-ansible.R }
```

License
-------

MIT

Author Information
------------------

Sean Ho, https://github.com/ho-ansible/
