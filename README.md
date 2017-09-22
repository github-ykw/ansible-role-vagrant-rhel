# ansible-role-vagrant-rhel
Install Vagrant on CentOS/RHEL7 - Top to Bottom - linuxbuff

Taken from Vagrant Quick Start in 15 Minutes guide at
https://linuxbuff.wordpress.com/2017/08/01/vagrant-quick-start-in-15-minutes/


Written to take a base CentOS or rhel server and install vagrant

Host Information:
CentOS Linux release 7.3.1611 (Core)
Software Install = @base


USAGE:

Create a yml file e.g.

---
- hosts: 192.168.1.97
  become: yes

  roles:
   - ansible-role-vagrant-rhel



