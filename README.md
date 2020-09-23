# Ansible role: R
Statistical software

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `R_cran_mirror` (default: http://cloud.r-project.org/)
+ `R_cran_ver` (default: cran40): R version
+ `R_pkgs` (default: docopt): list of R packages to install from CRAN
  `docopt` is a prerequisite for littler's `update.r` script.
+ `R_github_pkgs` (default: none): list of R packages to install from Github
+ `R_prereq_pkgs` (default: none): OS (not R) packages needed by any of
  the above R packages

## Playbooks
+ `main.yml`: apply role

## Dependencies
None.

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/
