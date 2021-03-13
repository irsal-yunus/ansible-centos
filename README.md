# ansible-centos
ansible centos
- install ansible on workstation
- make sure ansible connect to server
  - ansible all -m ping
- create iventory file for host server
- create roles using ansible-galaxy init roles_name --offline
- checking syntax ansible :
  - ansible-playbook -i iventory playbook.yml --syntax-check
- running playbook :
  - ansible-playbook -i iventory playbook.yml --ask-become-pass
