# dockeransible
Create docker virtual machiens from VMware Vsphere using ansible vspher_client and build Docker cluster. Details explanation is in my blog site [Alexjoh Blog](https://alexjoh.blogspot.ca) The goal of these script is building Prod, Test, and Dev environment, building docker cluster, and implemneting CI/CD using ansible for small team project. For repository, Artifactory OSS will be used. I've newbie on the Ansible and explained entire steps from the blog

## Antomation with Ansible(1) - Install Ansible 2.4.3 on CentOS 7.4

This will demonstrate how to install ansible on Centos 7

[Automatoin with Ansible 1](https://alexjoh.blogspot.ca/2018/04/Automation-Ansible-Install-on-CentOS-7.html)

## Automation with Ansible (2) - Create/Provisioning Virtual Machine using vsphere_client from VSphere environment

This will show you how to create or provision new virtual machine using vspher_client

[Automatoin with Ansible 2](https://alexjoh.blogspot.ca/2018/04/Automation-Ansible-Create-Provisioning-VM-using-vsphereclient-VSphere.html)


## Automation with Ansible (3) - Create/Provisioning Virtual Machine from Template using vsphere_client on VSphere environment

From this tutorial, we will create new VM from template file using vsphere_client.

[Automatoin with Ansible 3](https://alexjoh.blogspot.ca/2018/04/Automation-Ansible-Create-Provision-VM-Template-using-vsphereclient-VSphere.html)

## Automation with Ansible (4) - Display Cloned VM information with Ansible and vsphere_client

This will demonstrate how to collected information from Ansible and show the value on the scree

[Automatoin with Ansible 4](https://alexjoh.blogspot.ca/2018/04/automation-ansible-display-information-variable-debug-vspherclient.html)

##  Automation with Ansible (5) - Change/Manage IP from cloned VM

There is a challenge to manage hosts of cloned copies because template can't assign or change any information.

[Automatoin with Ansible 5](https://alexjoh.blogspot.ca/2018/04/automation-ansible-Change-Manage-IP-Cloned-VM.html)

##  Automation with Ansible (6) - DDNS(Dynamic DNS) implementation with DNS(BIND) and DHCP on CentOS 7

We've reviewed how to add dhcp static IP address from DHCP and how to add it using ansible. This tutorial will show how to update DNS entry dynamically as soon as new IP is added into DHCP.

[Automatoin with Ansible 6](https://alexjoh.blogspot.ca/2018/04/automation-ansible-implement-ddns-bind-dhcp-centos-7.html)

## Automation with Ansible (7) - Accessing inventory host variable from playbook

Before writing full script, I need to learn how to read variables from host file. I tried to use range varible from host variable, but this doesn't work.

[Automatoin with Ansible 7](https://alexjoh.blogspot.ca/2018/04/automation-ansible-access-variable-inventory-host-playbook.html)

## Automation with Ansible(8) - Running command on Remote computer

I need to run commands from remote and due to the password prompts, there was a challenge on it. To do this, "pexpect" module should be installed on the remote target computer and we will use "expect" and "responses" tag from ansible.

[Automatoin with Ansible 8](https://alexjoh.blogspot.ca/2018/04/ansible-automation-run-execute-shell-command-remote-using-expect-responses.html)