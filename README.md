# DB Replication for Ansible Tower

> This playbook is only tested with ansible-tower-setup-bundle-3.3.1-1.el7 on RHEL 7.

## Usage

- Install Ansible Tower with separate database server.

- Clone this repo in Ansible Tower server.

- Define master and replica in inventory file.

- Run `ansible-playbook -i inventory playbook.yml`


**Reference: [https://www.linkedin.com/pulse/building-ansible-tower-clusters-louay-shaat](https://www.linkedin.com/pulse/building-ansible-tower-clusters-louay-shaat)**