Ansible Role: Neofetch
=========

Installs [Neofetch](https://github.com/dylanaraps/neofetch) on RHEL/CentOS and Ubuntu/Debian.

Role Variables
--------------

Available role variables are listed below, along with default values:

    neofetch_version: "6.1.0"
    
The version of Neofetch to download and install.

    neofetch_prefix: "/usr/local"
    
The prefix to install Neofetch under. With the default prefix, Neofetch will be
installed to `/usr/local/bin/neofetch`.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
        - tmiller02.neofetch

License
-------

MIT
