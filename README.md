Example ansible configuration
=============================

Update `hosts` file with hostnames of servers to provision. 

With this example only rpm based systems containing a "memcached" package in their yum repos are supported.

Use the following to execute the changes.

Install ansible using python pip with `pip install ansible`.

Once ansible is installed, servers may be provisioned using the following command

```
ansible-playbook -i hosts -s playbooks/memcached-setup.yml
```
