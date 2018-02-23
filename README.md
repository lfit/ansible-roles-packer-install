packer-install
==============

Install packer.

Requirements
------------

None.

Role Variables
--------------

packer_checksum: Checksum of packer archive.
packer_version: Version of packer to install.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: lfit.packer-install
           packer_version: 1.1.3
           packer_checksum: sha256:b7982986992190ae50ab2feb310cb003a2ec9c5dcba19aa8b1ebb0d120e8686f

License
-------

MIT

Author Information
------------------

Linux Foundation Release Engineering
