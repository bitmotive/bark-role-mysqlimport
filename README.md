BARK: MYSQLIMPORT
=========

Automate a MySQL database restore

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**MYSQLIMPORT_DATABASE_NAME**:

The name of the database to import.

**MYSQLIMPORT_DATABASE_USERNAME**:

The MySQL who will connect to the databse.

**MYSQLIMPORT_DATABASE_PASSWORD**

The password of the MySQL user.

**MYSQLIMPORT_DATABASE_FILEPATH**

Where to find the DB file to import on the machine running Ansible.


Dependencies
------------

None known at the time, but only tested on Debian/Ubuntu machines.

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com 
