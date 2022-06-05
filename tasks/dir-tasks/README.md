# dir-tasks
> This playbook is responsible for creating/deleting/updating directories.

## Table of Contents
* [Usage](#usage)
---

## Usage 
> Refer to sample commands for every playbook file.
---
* ### create-dir.yml

    * `ansible-playbook tasks/dir-tasks/create-dir.yml --extra-vars "new_dir_name='extra_test'"`
    * `--extra-vars` or `e` is command line argument that can be used to specify variables at runtime.
    * Refer to [anisble documentation](https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html#defining-variables-at-runtime) for more details.
    * `vars_files` lets us use the variables declared variables under `group_vars/all`
---
* ### delete-dir.yml
    * `ansible-playbook tasks/dir-tasks/delete-dir.yml --extra-vars "rm_dir_name='extra_test'"`
    * `--extra-vars` or `e` is command line argument that can be used to specify variables at runtime.
    * Refer to [anisble documentation](https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html#defining-variables-at-runtime) for more details.
    * `vars_files` lets us use the variables declared variables under `group_vars/all`


