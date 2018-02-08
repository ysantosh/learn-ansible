# learn-ansible
ansible

```
use only role default , group_var aand playbook_var
roles -> vars should be only used for platform specific only

task sequence then use register.yml
debug module used to print variable and can be used for debugging.

ansible galaxy


Tags - selective execution
--list-tags
--list-tasks
--tags=
--skip-tags=
Pattern can be used and tags are inherited.

Magic variables can be used if the fact caching is enabled.
http://docs.ansible.com/ansible/devel/plugins/cache.html

ansible-config dump |grep -i cache

left out is
- vault
- application deployment
- module writing

````
