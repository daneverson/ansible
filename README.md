## How To Use This

I use this playbook to do an initial secure of a new digitalocean droplet. To do that, just add the server to the inventory and run the following:

```
$ ansible-playbook -i inventory.ini -u root playbooks/initial_secure.yml
```