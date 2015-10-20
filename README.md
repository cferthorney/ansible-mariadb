MariaDB
=========

Installs MariaDB 10.  Uses Maria Foundation's [own repositories](http://mariadb.org/mariadb/repositories/) using UK mirrors where possible.

Requirements
------------

This role requires Ansible 1.4 or higher.  Platform requirements are listed in the metadata file.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

* cferthorney.common


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: cferthorney.mariadb }

License
-------

BSD

Author Information
------------------

This was created in 2015 by David Thorne [cferthorney](https://www.davidthorne.net) with influence from [Ansible for DevOps](http://ansiblefordevops.com/) by [Jeff Geerling](http://jeffgeerling.com/)
