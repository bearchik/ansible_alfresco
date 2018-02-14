# Ansible playbook for Alfresco
Ansible playbook for install Alfresco to Ubuntu or Debian

## Prerequisite
- Installed Ubuntu or Debian
- Installed Ansible version 2.2 or more
- Alfresco installation package for linux - You can get it from [Alfresco official site](https://www.alfresco.com/alfresco-community-editions)

## Installation
- Put your alfresco distrib to **../roles/alfresco/files** with name **alfresco.bin**
- Change **../roles/alfresco/files/install_ops.txt** if this need.
- Write your server ip or name in inventory file in **alfresco** group.
- Run **ansible-playbook ./alfresco.yml** in console

## License
BSD

## Author Information
You can send email to: bearchik@gmail.com
