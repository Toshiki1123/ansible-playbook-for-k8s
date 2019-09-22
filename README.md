# Ansible Playbook for kubernetes multi master

An Ansible Playbook that installs kubernetes multiple master on Linux.  
Attention: This Playbook is disabled firewalld.

## Requirement
???

## How to
1. OS install each servers.  
2. Copy hosts.sample. Set IP Address and SSH user.
3. Run presetup.yml
4. Run lb.yml and k8s-maseter.yml, k8s-worker.yml
5. Let's Enjoy!!

## TODO
* Multi master.
* Set Kubernetes Version.
* and more...