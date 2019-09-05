Thoth: PostgreSQL
=================

This role will deploy PostgreSQL into an OpenShift namespace.

Role Variables
--------------

This role requires a namespace in which the metrics exporter should be created together with few parameters for PostgreSQL instance. See the ``vars`` configuration section for more info.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters):

    - hosts: localhost
      connection: local
      gather_facts: False

      roles:
        - role: thoth-station.postgresql
          namespace: thoth-test-core

License
-------

GPLv3

Author Information
------------------

The Thoth Station Team.