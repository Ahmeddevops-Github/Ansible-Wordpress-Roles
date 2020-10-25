Role Variables
--------------

Dependencies
------------
  - ahmeddevops.php
  - ahmeddevops.apache

Example Playbook
----------------
  roles:
    - role: ansible-role-php
      vars:
        php_version: "7.4"
    - role: ansible-role-apache
    - role: ansible-role-wordpress

License
-------
MIT

Author Information
------------------
Ahmed Devops


