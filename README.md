# dots
## What
Installation and configuration of tools that I like.
## How
Ansible.
## Where
Ubuntu 16.04, but potentially on other debian/ubuntu hosts. YMMV.
## Setup
```
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
ansible-playbook install.yml -K
```
Groovy... 🕶️
## Notes
Roles were probably overkill but eh.
