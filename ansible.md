#### Install Prerequisites

Not quite sure if openshift-ansible installs the [prerequisites](https://docs.openshift.org/latest/install_config/install/prerequisites.html) or not.  So I created a quick playbook under [ansible](ansible) that will install them for you.  The only caveat is the docker-storage-setup which is defined for my specific setup.

```
ansible-playbook -i ansible/inventory/hosts.ini ansible/site.yml
```
