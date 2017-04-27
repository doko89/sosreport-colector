## Sosreport Collector

Tool to generate sosreport and collect file from server

### Requirement

- ansible
- sshpass

# Centos/Rhel/Fedora

sudo yum install sshpass

# debian/ubuntu

sudo apt install sshpass

### Example

ansible-playbook -i inventory sosreport.yml
ansible-playbook -i inventory pull.yml

