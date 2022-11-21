# Anible-roles
ansible roles to install git, mongodb and apache


$ ansible-galaxy init my-role

$ sudo ansible-galaxy init prerequisites
$ sudo ansible-galaxy init mongodb
$ sudo ansible-galaxy init apache

role —>  tasks —> main.yml
for example
cd prerequisites/tasks/ && nano main.yml

To ensure that the packages were installed successfully, we are going to check their versions
$ mongod --version
$ apachectl -v
$ git --version
