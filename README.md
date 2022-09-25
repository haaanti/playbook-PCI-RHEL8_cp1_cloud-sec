Requirements
------------

- Ansible version 2.9 or higher

How to use
----------------

Edit `hosts` file according to your preference.

Next, test the playbook using the following example:

    ansible-playbook -i hosts --check playbook.yml

To deploy it, use:

    ansible-playbook -i hosts playbook.yml
