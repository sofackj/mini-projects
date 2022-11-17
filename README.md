# Some Mini-Projects during our long Devops Journey

## Ansible Project I : May be used for docker containers <directory>

### What you will see

- Variables as lists
- Combination of modules as :
  - include_tasks
  - with_items
  - when
- Use of tags to filter our tasks
  
### Where to go

- Clone the repository

<git clone https://github.com/sofackj/mini-projects.git>
  
- Every connection is local so start the playbook with this command
  
<ansible-playbook mini-projects/ansible_and_vars/my-playbook.yml>
  
- Tags can be used as <todo> and <check>

<ansible-playbook mini-projects/ansible_and_vars/my-playbook.yml --tags todo>
