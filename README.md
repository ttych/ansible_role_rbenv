Role Name
=========

Install rbenv in target user homedir.

rbenv install is composed of :
- rbenv
- ruby-build (rbenv plugin)
- rbenv-default-gems (rbenv plugin)
- rbenv-each (rbenv plugin)
- rbenv-vars (rbenv plugin)

Requirements
------------

None.

Role Variables
--------------

Look into defaults/main.yml.

Example Playbook
----------------

Example for installing rbenv into app_user homedir:

    - hosts: servers
      roles:
         - { role: rbenv, become: yes, become_user: app_user }

License
-------

BSD
