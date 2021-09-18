# Ansible-Basics

Hi the playbooks I'm creating are for basic system use in Linux for daily sys admin task.
plase use the below syntax to excute the playbook with sudo privileges.

$ ansible-playbook "playbook name" -K 

example as below

$ ansible-playbook installpkg.yml -K
