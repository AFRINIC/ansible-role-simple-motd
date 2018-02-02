# Ansible Role: AFRINIC.simple-motd


Simple MOTD for AFRINIC systems

Role Variables
--------------

`motd_host_string:   "{{ inventory_hostname }}"`

Defines a custom, descriptive string to add into the MOTD template. Defaults to the hostname, but can be any one-line detail about the host.

`motd_contact_email: "sysadmin-team@afrinic.net"`

Self-explanatory.


Example Playbook
----------------


    - hosts: all
      roles:
         - { role: AFRINIC.simple-motd, tags: ['motd'] }

License
-------

Apache 2.0
