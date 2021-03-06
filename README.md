# Policy Template

This repository contains security policy templates that can be adopted by organizations of different sizes.
It is in support of securityprogram.io.

## Versions

There are several branches which we intend to support different levels program:

* main - is for the most complete NIST 800-53 aligned policies
* simple - is for the simplest policy you can start with

We are exploring additional levels and a progressive flow through the branches.

## How To Use the Templates

These templates are being developed to use with securityprogram.io.

## Export to other formats

Using [Pandoc](https://pandoc.org) it is possible to easily convert the markdown files in the repository to other
formats (e.g. Microsoft Word).

1. [Install Pandoc](https://pandoc.org/installing.html). Brew and Chocolatey packages are available to make this easy
   on Mac or Windows systems.
1. Run the export script. On Mac/Linux `export_to_word.sh`. On Windows `Export-PolicyToWord.ps1`.

## Limitation of Liability

These policy templates are provided as a guide for what we believe are best practices.  *We cannot be responsible for
whether the policy is complete or whether it is followed.*
