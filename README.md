# ASD - ACN - Ansible and OpenStack

This project is a set of ansible script to up and make a provision of an OpenStack cloud. The result code was developed as a part of the Cloud Computing Architecture discipline, in the Distributed Software Architecture postgraduate, at PUC Minas.

### Instructions to run
1. Clone this repository in a minimum Linux
2. Run the following commands inside your terminal:
    1. `. openrc.sh`
    1. `ansible-playbook asd-acn-openstack-and-ansible/install-dependencies.yml`
    1. `ansible-playbook asd-acn-openstack-and-ansible/install-openstack.yml`
3. You can now visit the URL http://<your-gcp-external-ip>/dashboard/

### About the environment
- GCP
- Ubuntu 16.04
- Ansible 2.3.2.0
- Python 2.7.12
- OpenStack 3.12.0

## Released versions

### v0.0.1
- Script to install OpenStack and its dependencies
