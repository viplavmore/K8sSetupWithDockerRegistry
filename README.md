# K8sSetupWithDockerRegistry
Ansible : K8S Setup With Docker Registry
This ansible script creates the Private Local Docker Registry and also setup the Kubernetes Cluster.

We can run this file directly as playbook or else we can play as a ROLE.

In case of role, place the variable code on "/roles/\<rolename\>/vars/main.yml" and remaining code is in "/roles/\<rolename\>/tasks/main.yml" files. Also, mentioned the below details as per your requirement:
  - Docker Registry IP
  - Nameserver IP 1
  - Nameserver IP 2
  - Docker Registry Name
  - Username


** NOTE: While creating Ansible Directory Structure, use this command : **"#ansible-galaxy init rolename"** **
