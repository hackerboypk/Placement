DEVOPS interview question and theory
Devops ?? pending


Git














===================================================================================================================================================================
what is ansible ?
Ansible is a software configuration management tool to deploy an application using ssh without any 
downtime. It is also used for management and configuration of software applications. Ansible is 
developed in Python language.

 Working process of Ansible?
Here we crate file called playbook and inside playbook we write script in YAML format to create infrastructure. Once we execute this playbook, automatically code will be converted into Infrastructure. We call this process as IAC 
(Infrastructure as Code). We have open source and enterprise editions of Ansible. Enterprise edition we call Ansible Tower

Ansible components?
Server: – It is the place where we create playbooks and write code in YML 
format
Node: – It is the place where we apply code to create infrastructure. Server 
pushes code to nodes.
Ssh: – It is an agent through ansible server pushes code to nodes.
Setup: – It is a module in ansible which gathers nodes information.
Inventory file:- In this file we keep IP/DNS of nodes.

What are the Advantages of Ansible?
• Agentless, it doesn’t require any extra package/daemons to be installed
• Very low overhead
• Good performance
• Idempotent
• Very Easy to learn
• Declarative not procedural

An Ansible inventory file is a configuration file that contains a list of hosts and groups that Ansible can manage. The inventory file defines the target hosts on which Ansible will run tasks, and provides additional information about those hosts such as the host's IP address, port, and connection type.

Here's an example of what an Ansible inventory file might look like:

python
Copy code
[web]
webserver1 ansible_host=192.168.1.100 ansible_user=ubuntu
webserver2 ansible_host=192.168.1.101 ansible_user=ubuntu

[db]
database1 ansible_host=192.168.1.102 ansible_user=ubuntu

[all:vars]
ansible_python_interpreter=/usr/bin/python3
