Ansible deployment playbook for wordpress sites running on ubuntu 14.04.

Example:
```
$ ansible-playbook site.yml --extra-vars "src_dir=/home/somebody/git/site server_hostname=site.tld" -i hosts
```

TODO:
* Master-slave replication (ex: master in sf, slave in london)
* Task for backing up mysql
* Task for loading mysql from backup
