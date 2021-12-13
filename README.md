# Ansible role: R
Statistical software

## Requirements
Debian 10, 11.

## Role Variables
+ `R_pkgs` (default: none): list of R packages to install from CRAN
+ `R_sys_pkgs` (default: none): OS (not R) packages to install
+ `R_etc_R`: dict of (path, contents) pairs for files to add under `/etc/R/`

## Playbooks
+ `main.yml`: apply role

## Dependencies
None.

## License
Ansible role licensed [MIT](LICENSE).

## Author Information
Ansible role by [Sean Ho](https://github.com/ho-ansible/)
