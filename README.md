Role Name
=========

Install docker on centos

Requirements
------------

- Centos 7

Role Variables
--------------

None

Dependencies
------------

- None

Example Playbook
----------------

Install

  ansible-playbook -i inventory.txt tasks/main.yml -u cc

Run the test again

  ansible-playbook -i inventory.txt tasks/helloworld.yml -u cc

Including an example of how to use your role (for instance, with variables passed in as parameters)
is always nice for users too:

    - hosts: servers
      roles:
         - { role: cloudmesh.cloudmesh-ansible.main }

License
-------

Apache 2.0

Author Information
------------------

Gregor von Laszewski (laszewski@gmail.com)
