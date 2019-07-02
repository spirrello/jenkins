# Repo for deploying Jenkins and managing it's configuration.


Requirements
2 x servers
 - master
 - agent (no Jenkins installation required)
- install jenkins
- install nginx
- Update or add another environment with the master and agent servers, e.g., playbooks/environments/{MYENV}


Example Installation Process:

```
ansible-playbook  -i playbooks/environments/virtualbox/inventory playbooks/install_jenkins.yml
```



