Debian-Gitlab-ce
================

Code, test, and deploy together

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

- cowops.debian-postfix

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-gitlab-ce }

Tasks
-----

  - Install dependencies
  - Install [gitlab-ce](https://about.gitlab.com/)


License
-------

BSD
