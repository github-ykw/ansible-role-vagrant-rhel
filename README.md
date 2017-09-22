Role Name
=========

This role has been created from the steps from post Vagrant Quick Start in 15 Minutes at https://linuxbuff.wordpress.com/2017/08/01/vagrant-quick-start-in-15-minutes/


Requirements
------------

This role will take a base CentOS/RHEL 7 server and Install Vagrant

Tested on:
 CentOS Linux release 7.3.1611 (Core)
 Software Install = @base


Role Variables
--------------

There are 3 variables currently configured:

sleeptime - time taken to allow the server to reboot
markerfile1 - file laid down to prevent reboot if role is re-run
vagrantrpm - the Vagrant RPM URL


Dependencies
------------

None


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: yes
      roles:
         - ansible-role-vagrant-rhel
         

License
-------

BSD

Author Information
------------------

Author: LinuxBuff https://linuxbuff.wordpress.com
