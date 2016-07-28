OpenStack-Ansible MongoDB
##########################
:tags: openstack, mongodb, cloud, ansible
:category: \*nix

This Ansible role installs and configures Mongodb with Replication and Sharding for use with OpenStack Ansible.

Default Variables
=================

.. literalinclude:: ../../defaults/main.yml
      :language: yaml
   :start-after: under the License.

Required Variables
==================


Example Playbook
================

.. code-block:: yaml

   - name: Installation and setup of MongoDB
     hosts: mongodb_all
     user: root
     roles:
       - role: "os_mongodb"
     vars:

Tags
====

