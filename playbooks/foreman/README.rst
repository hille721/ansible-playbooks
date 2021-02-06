About
=====

* create a VM with `Foreman <https://www.theforeman.org/>`_/ `Katello <https://theforeman.org/plugins/katello/>`_ for testing purposes installed on your client
* only one command necessary for provisioning:
* the nightly build will be installed

    .. code-block::

        cd ./foreman-katello
        vagrant up


Requirements
============

* `Vagrant <https://www.vagrantup.com/>`_
* as provisioner for Vagrant **libvirt** is used 
(could be changed in the ``Vagrantfile``)


Project structure
=================

* ``foreman_katello/``: provision VM with Foreman/Katello with Ansible plugin installed
* ``foreman_server/``: provision VM with Foreman with Ansible plugin installed (tbd)
* ``foreman_testvms/``: provision 4 test VMs (Debian10, Ubuntu20, Suse15, CentOS8)
