Gerrit P.O.C.
-----
This is a demo instance of gerrit ansible script for testing purposes.
It uses apache2 htpassword for authentication!!!
You must upload a public key to be able to do whatever too!

Use ssh method for clone / push / pull

OS: Centos 7

Usage: 
- Update the inventory file with the current IP
- Set FQND in /etc/hosts (xxx.xxx.xxx.xxx   gerrit.local )
- Choose a gerrit release from: https://gerrit-releases.storage.googleapis.com/index.html
- Set the release in the group_vars
- Create SSH keys ( createsshkeys.sh )


```
Run: ansible-playbook -i inventory.yml gerrit.yml
```

Url: http://gerrit.local/

Default user: gerrituser

Password: password123

___Enjoy!___
