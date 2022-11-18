# ANSIBLE ROLE FOR KUBERNETES NOTE APP

## PRE-REQUISITES

### 1. PACKAGE INSTALLATIONS [Ubuntu]

```
sudo apt update
sudo apt upgrade
sudo apt install ansible
ansible-galaxy collection install kubernetes.core
ansible-galaxy collection install community.kubernetes
ansible-galaxy collection install cloud.common
sudo apt-get -y install python3-pip
pip install openshift
```
