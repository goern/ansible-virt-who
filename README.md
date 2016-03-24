goern.virt-who
==============

[![Build Status](https://travis-ci.org/goern/ansible-virt-who.svg?branch=master)](https://travis-ci.org/goern/ansible-virt-who)

This will configure virt-who on Red Hat Enterprise Linux 7. By now it is only
capable of configuring virt-who for VMware in conjunction with Red Hat Satellite 6.


Requirements
------------
None

Role Variables
--------------
None

Dependencies
------------
The RHEL host must have a valid subscription to install the virt-who package.

Example Playbook
----------------
    - hosts:
        - rhel-virtwho-server
      roles:
        - goern.virt-who

License
-------
GPLv3

Author Information
------------------
Christoph Görn <goern@redhat.com>

References
----------

 * https://access.redhat.com/documentation/en-US/Red_Hat_Subscription_Management/1/html/RHSM/register-virtual.html#rhsm-virt-vmware
 * https://access.redhat.com/documentation/en-US/Red_Hat_Satellite/6.1/html-single/Installation_Guide/index.html#sect-Red_Hat_Satellite-Installation_Guide-Managing_Hypervisors_and_Virtual_Guest_Subscriptions-Setting_up_a_VMware_Hypervisor
