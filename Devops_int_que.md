DEVOPS interview question and theory
Devops ?? pending


Git
=====================================================================================================================================================================

What is Maven ?
Maven is build Tool and a automation and project management tool devloped by apache software fondation based on POM (project object models)
->Maven co=an build any of project into desired output such as .jar , .war or metadata
->mostly used for java based projects


features of Maven:

Dependency Management: Maven simplifies dependency management by allowing you to declare the dependencies for your project in the POM file, and automatically downloading and installing those dependencies from remote repositories.

Build Lifecycle: Maven defines a standard build lifecycle with well-defined phases for compiling code, running tests, packaging the application, and deploying the artifacts.

Convention over Configuration: Maven uses a convention over configuration approach, which means that it follows a standard project structure and file naming conventions, making it easier to set up and configure a project.

Central Repository: Maven has a central repository that contains a large number of open-source libraries, making it easy to find and use third-party libraries in your projects.

Plugins: Maven provides a large number of plugins that can be used to extend its functionality. These plugins can be used for tasks such as generating documentation, creating reports, or integrating with other tools.

Customization: Maven is highly customizable and can be configured to suit the needs of different projects. This includes defining custom build phases, creating custom plugins, and configuring the build process.

Continuous Integration: Maven is often used in conjunction with continuous integration (CI) tools like Jenkins or Travis CI, allowing for automatic builds and testing of your codebase with each code commit


Maven lifecycle 
Build lifecycle consist of a sequnce of build phase and each build phase consist of a sequnce of gools. each goal is reponsible for a particuler task.
1 genrated resource  (means download dependence from remote or local repo)
2 comple code ( )
3 unit test
4 Package (build in jar or war )
5 install (save into local repo & artifactory)
6 Depoly (to server)
7 clean (Delete run time files)









































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


What is ad-hoc command ?
An Ansible ad-hoc command is a one-line command used to execute a single Ansible module on one or more target hosts. It's a quick and easy way to run ad-hoc commands or perform simple tasks without creating a playbook.

(ad-hoc command is linux command.it dont have idempontancy(over right) .it do not prefer but sometimes used for small task like start the machin or stop the machin or install any package 

Here's the basic syntax for an Ansible ad-hoc command:
=Ansible <host-name> -a <argument>  <what you want to do.>
 

 
 Ansible playbook ?
 An Ansible playbook is a set of instructions that are used to define and execute a series of tasks in a specific order on a set of remote hosts. Playbooks are written in YAML format, which is a human-readable data serialization format. Ansible uses these playbooks to manage and configure remote systems, automate deployment processes, and perform other system administration tasks.
 
 (Ansible playbook means collaction or set of models and task in the playbook by using playbook we can parform service ,configure, any thing to the node servicer) 
 ---
- name: Install Apache
  hosts: webservers
  become: true
  tasks:
    - name: Install Apache package
      yum:
        name: httpd
        state: present
 - name: Restart Apache
      service:
        name: httpd
        state: restarted
 
 what is model in ansible ?
 Modules: Ansible uses modules to perform specific tasks on remote hosts, such as installing packages, copying files, managing users, and starting or stopping services. Modules are reusable and can be used in multiple playbooks. Ansible includes a wide range of built-in modules, and you can also create your own custom modules. (it have idempontancy(over right))
 
 
 
 
 
 
 
 
 
 
