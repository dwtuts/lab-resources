# Ansible playbook to configure docker and setup kubernetes on my local lab. 

Run the command with
```ansible-playbook -i kube-inventory playbook.yml --extra-vars "ansible_become_pass=""
```