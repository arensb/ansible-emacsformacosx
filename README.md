Role Name
=========

Download and install Emacs from emacsformacosx.com

### Notes

This role downloads Emacs directly to the client. This is fine for small installations, but if you have anything over half a dozen hosts, I would recommend downloading the `.dmg` file to one central host and distributing it to the clients. That is beyond the scope of this role, though.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

`dest_dir`: Directory in which Emacs should be installed. Default: `/Applications`.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: macs
      roles:
        - role: emacsformacosx
		  vars:
		    version: 25.1

License
-------

BSD

Author Information
------------------

Andrew Arensburger, https://www.ooblick.com/
