# ansible-deploy-test
Just a test deploy playbook using Ansible

To deploy a test httpd container to the Docker systems in the dev DMZ:
```
ansible-playbook playbooks/deploy-httpd.yaml
```

To remove the test httpd container deployment from the Docker systems in the dev DMZ:
```
ansible-playbook playbooks/remove-httpd.yaml
```
