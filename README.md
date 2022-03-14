IC-IT Polkit VDI fixer
=========

This role fixes polkit actions on VDI machines in order to allow users to shutdown and reboot machines.

Requirements
------------

This roles relies on the following package: python3-lxml
This package is used to manipulate the polkit XML action file.
**It is automatically installed by the role.**

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
      - ic_it.polkit_vdi_fixer

License
-------

BSD

Author Information
------------------

Emmanuel Jaep (EPFL IC-IT)
