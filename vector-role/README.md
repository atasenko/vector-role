vector
=========

Simple Vector deploy and configure role

Role Variables
--------------

| vars           | description                     |
|----------------|---------------------------------|
| vector_version | Version of Vector to install    |
| vector_apps    | List of applications for Vector |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector }

License
-------

MIT

Author Information
------------------

Aleksei Tasenko