# ansible-docker

Important : Configure invetory /etc/ansible/hosts

```{r, engine='bash', count_lines}
$ git clone git@github.com:gloria-sentinella/ansible-docker.git 
$ cd ansible-docker
$ cp -r docker /ect/ansible/roles/
$ ansible-playbook playbook-install-docker-all-hosts.yml
```
