# Role path
By default, Ansible looks for roles in two [locations](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html):

- in a directory called roles/, relative to the playbook file
- in /etc/ansible/roles

If you store your roles in a different location, set the **roles_path** [configuration](https://docs.ansible.com/ansible/latest/reference_appendices/config.html#default-roles-path) option so Ansible can find your roles. 

Example :
$ cd ansible_role_parent_directory
$ export ANSIBLE_ROLES_PATH="$PWD"

