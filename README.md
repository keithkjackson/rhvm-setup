# rhvm-setup
Playbook for installing a Red Hat Virtualization Manager and performing common operations in a Red Hat Virtualization Environment



rhvm-setup:
This will configure a System or VM to Register to a Satellite, enable the required repositories, install the packages, and perform the engine-setup without any user input.

External and Hosted-Engine deploys can be accomplished with the playbook roles.
Edit vars to specific environment before running.

aaa-ldap:
This role will configure an External LDAP Source for authentication to the RHV Manager.
Edit vars to specific environment before running.

  
