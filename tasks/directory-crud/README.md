# directory-crud
> These are tasks responsible for creating/deleting/updating directories.

## Table of Contents
* [Usage](#usage)
---

## Usage 
> Refer to sample commands for every playbook file.
---
* ### create-dir-task.yml

    * `state:directory` means to create a new directory.
---
* ### remove-dir-task.yml
    * `state:absent` means to remove the mentioned directory.

* ### tags
    * We can use tags to execute or skip selected tasks only.
    * Refer to [Tags Documentation](#https://docs.ansible.com/ansible/latest/user_guide/playbooks_tags.html).

---

## Room for Improvement
TODO's to be added. 

To do:
- Check whether the directory is empty or not before deleting.


