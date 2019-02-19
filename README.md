# Ansible role: R
Statistical software: 
base R runtime only, no extra packages.

You may install packages manually via, e.g.
```
/usr/lib/R/site-packages/littler/examples/install.r tidyverse
```

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `R_cran_mirror`: URL from which to download packages, see [mirror list](https://cran.r-project.org/mirrors.html)
+ `R_cran_ver`: R version, e.g., `cran35` for R v3.5.x
+ `R_packages` (default: future, tidyverse): R packages to install 
+ `R_github_packages` (default: none): R packages to install from Github

## Dependencies
None.

## Example Playbook

```
- hosts: R
  roles:
    - { role: ho-ansible.R }
```

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/
