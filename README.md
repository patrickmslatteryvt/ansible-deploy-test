# ansible-deploy-test
Just a test deploy playbook using Ansible. Used for Jenkins pipeline testing.

To deploy a test httpd container to the Docker systems in the dev DMZ:
```
ansible-playbook playbooks/deploy-httpd.yaml --extra-vars "deploy=true" -v
```

To remove the test httpd container deployment from the Docker systems in the dev DMZ:
```
ansible-playbook playbooks/deploy-httpd.yaml --extra-vars "remove=true" -v
```
