Role Name
=========

This ansible role will install the current version of [Nextcloud](https://nextcloud.com/).

The LAMP portion of this role is based on [Digitial Ocean LAMP install guide](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04). I plan to break this out as a seperate role.

The Nextcloud portion is also based on a [Digital Ocean install guide](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-nextcloud-on-ubuntu-16-04).

Requirements
------------

- LAMP Stack (currently contained within the role)
- SSL Cert (use a properly issued cert, not self-signed)


Role Variables
--------------

There are a service account user/pass and a database user/pass that can be specified in defaults/main.yml.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

[github.com/gigaturtle](https://github.com/gigaturtle)
