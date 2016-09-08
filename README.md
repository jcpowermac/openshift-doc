## OpenShift Origin Setup

Documentation/notes in my deployment of OpenShift Origin v1.2.1.
Work in progress...

### Environment

All running on Fedora 24 Server (KVM)
- 2 x FreeIPA (DNS)
- 1 x master
- 2 x nodes

The master and two node virtual machines are just clones and sysprep'ed via `virt-sysprep`.  Each as two disks, the second disk is for the docker volume group.


- [DNS Configuration](dns.md)
- [Ansible Prerequisites](ansible.md)
- [OpenShift Install](openshift.md)
