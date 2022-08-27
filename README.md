# ansible_ubuntu_
Ansible role installing Firefox using the firefox deb package provided by the Ubuntu Mozilla Team.

Useful in case you do not want to install Firefox using the default Ubuntu 22 firefox deb (which is just a wrapper for the firefox snap.)

### Tested on
Ubuntu 22.04

### Tested with
Ansible 2.10

### Requirements
none (NOTE: while I haven't tested this, there is a chance the role *might* not work correctly if the default Ubuntu firefox deb and the firefox snap are present)

### Vars
none

### Credits
https://fostips.com/ubuntu-21-10-two-firefox-remove-snap/
