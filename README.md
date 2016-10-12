# Ansible and AWS Assumed Roles

This is a repo of example code to perform ansible tasks with assumed roles.

It is explained in my blog post:
http://www.drivenbydevops.io/aws-ansible-and-assumed-roles/                                                             

Items in the aws directory are to be placed in the .aws folder in the homedir
of the user/account running the ansible tasks. All other items can exist in a
working directory.

Requirements:
* Ansible 2.2.0
* Pre-configured AWS accounts (default account and account to assume role into)
