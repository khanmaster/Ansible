# Ansible
Infra Structure as Code with Ansible to provision multi server
What is “Infrastructure As Code”?
Infrastructure as code (IaC) is the way of defining computing and network infrastructure through source code, the same way you do for applications. Rather than manually configuring your infrastructure or using a one-off isolated script, IaC gives you the power to write code, using a high-level language, to decide how infrastructure should be configured and deployed.
Deference - IaC is different from infrastructure automation, which involves repeating the steps multiple times and spawning them on several servers.
Why IAC - The guiding principle behind IaC is to enforce consistency among DevOps team members by representing the desired state of their infrastructure via code. Moreover, the code can be kept in source control, which means it can be audited, tested on, and used to create reproducible builds with continuous delivery
Understanding Ansible concepts - timings 60-90 minutes to complete
Pre-requisites
None
This lesson covers:
Installing Ubuntu 18.04 LTS on Windows 
Creating 2/3 VMs on Windows using vagrant to create a Multi server/machin Dev Environment
Ansible Provisioning from Linux Ubuntu into VMs on Windows created with Vagrant 
creating SSH connectivity 
provisioning VMs with ansible adhoc commands
provisioning VMs with ansible playbooks to install Nginx and Mysql on different servers 
