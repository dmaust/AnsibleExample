Example ansible configuration
=============================

Update `hosts` file with hostnames of servers to provision. 

With this example only rpm based systems containing a "memcached" package in their yum repos are supported.

Use the following to execute the changes.

Install ansible with `pip install ansible` and then execute the changes with the following.

```
ansible-playbook -i hosts playbooks/memcached-setup.yml
```
