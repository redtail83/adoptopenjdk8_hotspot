Ansible Role: AdoptOpenJDK 8 HotSpot
=========

Install AdoptOpenJDK 8 HotSpot for Linux.

Requirements
------------

None.

Role Variables
--------------

Here is the list of all variables for this role.
```yml
# Base URL of AdoptOpenJDK 8 HotSpot download site.
site_url: https://github.com/AdoptOpenJDK/openjdk8-binaries/releases/download

# JDK version.
jdk_version: 8u212
```

Dependencies
------------

None.

Example Playbook
----------------

CentOS 7:

    - hosts: servers
      roles:
         - { role: redtail83.adoptopenjdk8_hotspot }

License
-------

MIT
