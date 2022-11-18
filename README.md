# ANSIBLE ROLE FOR KUBERNETES NOTE APP

## PRE-REQUISITES

### 1. Ansible Installation [Ubuntu]

```
sudo apt update
sudo apt upgrade
sudo apt install ansible
```
### 2. Dependency Packages Installation [Ubuntu]

```
ansible-galaxy collection install kubernetes.core
ansible-galaxy collection install community.kubernetes
ansible-galaxy collection install cloud.common
sudo apt-get -y install python3-pip
pip install openshift pyyaml
```
