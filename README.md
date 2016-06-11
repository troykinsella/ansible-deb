troykinsella.deb
================

Download and install deb packages.

Role Variables
--------------

* deb_package_dest: Optional. The local directory into which the deb will be downloaded. Default: /tmp.
* deb_package_url: The URL at which the deb can be downloaded.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: troykinsella.deb
           deb_package_url: https://releases.hashicorp.com/vagrant/1.8.3/vagrant_1.8.3_x86_64.deb

License
-------

MIT
