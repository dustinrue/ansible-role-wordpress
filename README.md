Wordpress
=========

Installs wordpress

Requirements
------------

Dependencies for this role will be installed at the same time.

Role Variables
--------------

There are no variables yet

Dependencies
------------

Requires dustinrue.xenial-bootstrap, dustinrue.mysql, dustinrue.nginx

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      become: yes
      gather_facts: no

      roles:
        - dustinrue.xenial-bootstrap
    - hosts: <host>
      become: yes
      gather_facts: yes

      roles:  
         - dustinrue.nginx
         - dustinrue.mysql
         - dustinrue.wordpress

License
-------

MIT

