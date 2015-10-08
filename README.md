timezone
========

Set the timezone.

Role Variables
--------------

 * timezone: UTC

    Specifies the timezone to set on the server. Should correspond with
    IANA timezone name (eg, US/Eastern or America/Chicago.)

Example Playbook
----------------

    - hosts: servers
      roles:
         - timezone

License
-------

BSD

Author Information
------------------

Adam Herzog <adam@adamherzog.com>
