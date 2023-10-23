K6
=========

This role perfom and install k6 package for Linux (Debian/RHEL families) and MAC (using brew).

Requirements
------------

- Ansible
- Brew (MACOs)

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

``` yaml
    - hosts: servers
      roles:
         - k6
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

Test
----

``ansible-playbook tests/test.yml -i tests/inventory --syntax-check`
