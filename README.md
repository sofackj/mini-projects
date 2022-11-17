# Some Mini-Projects during our long Devops Journey

## Ansible Project I : May be used for docker containers **```ansible_and_vars```**

### What you will see

- Variables as lists
- Combination of modules as :
  - include_tasks
  - with_items
  - when
- Use of tags to filter our tasks
  
### Where to go

- Clone the repository

```sh
git clone https://github.com/sofackj/mini-projects.git
```
  
- Every connection is local so start the playbook with this command

```sh
ansible-playbook mini-projects/ansible_and_vars/my-playbook.yml
```

- Tags can be used as <todo> and <check>

```sh
ansible-playbook mini-projects/ansible_and_vars/my-playbook.yml --tags todo
```
