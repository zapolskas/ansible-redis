# ansible-redis

Ansible playbook to install nginx from source and redis on inventory servers

## Environment

- OS: Windows 10 Version 1903 (OS Build 18362.657)
- Hypervisor: Microsoft Hyper-V 10.0.18362.1
- Ansible: 2.7.12
- Python: 2.7.15+ 
- VM CentOS: CentOS Linux 7 (Core) Linux 3.10.0-957.el7.x86_64
- VM Ubuntu server: Ubuntu 18.04.4 LTS Linux 4.15.0-91-generic

## Prerequisites

Ansible control node should be able to connect to managed nodes. Username ansible. Managed nodes IP address should be updated in file named production.

## Deployment

```sh
git clone https://github.com/zapolskas/ansible-redis.git
cd ansible-redis
ansible-playbook -i production site.yml
```
