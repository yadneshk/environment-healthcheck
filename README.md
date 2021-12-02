# Review Red Hat OpenStack Environment Health

```
$ git clone https://github.com/openstack-healthcheck/environment-healthcheck.git 
$ cd environment-healthcheck/
$ source ~/stackrc
$ tripleo-ansible-inventory --static-yaml-inventory inventory.yaml
$ ansible-playbook -i inventory.yaml ./playbooks/<playbook_name>.yaml
```
