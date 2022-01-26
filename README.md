# Upgrade_testing
Automate Upgrade Testing for glusterfs

# Prerequisites
1. Ansible
2. Vagrant
3. Virtual Box

# Set Up
1. Spin up 3 servers using [Vagrant script](Vagrantfile) provisioned by [Ansible script](provision.yaml)

# Steps
1. script to set-up firewall and ports
2. script to install old glusterfs version with downloaded rpms
3. script for all volume tasks - use gluster.ansible
4. script to install new glusterfs version with downloaded rpms
5. script to check all works fine
