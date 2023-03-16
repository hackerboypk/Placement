DEVOPS interview question and theory
Devops ?? pending


Git
=====================================================================================================================================================================
jenkins

what is sofware ?
collaction of program is called sofware

types of sofware ?
1) application software - Application software is a type of software that is designed to perform specific tasks or solve specific problems.
2) system software -System software is a type of software that manages and controls the operation of a computer or electronic device. ex operating systems, device drivers, firmware, and utility programs. ex  software include word processors, spreadsheet programs, email clients, web browsers, media players, and graphic design software.

what is sdlc (sofware developing life cycle )
SDLC stands for Software Development Life Cycle, which is a methodology used to develop software systems. It is a process for planning, designing, developing, testing, implementing, and maintaining software applications.

phase of the Software Development Life Cycle (SDLC):

Planning Phase: In this phase, the project scope, objectives, and goals are defined, and the stakeholders and their requirements are identified. A project plan is created that includes timelines, budgets, resources, and deliverables.

Analysis Phase: During this phase, the requirements of the system are gathered, documented, and analyzed. The functional and non-functional requirements of the software are identified, and the data inputs and outputs are defined. The process flow is defined, and use cases and user stories are developed. The outcome of this phase is a Requirements Specification document that outlines the requirements of the software.

Design Phase: In this phase, the software architecture and design are developed based on the requirements identified in the analysis phase. The technical specifications are created, and the software components are defined. The user interface design is developed, and the software is prototyped. The outcome of this phase is a Design Specification document that outlines the software architecture and design.

Development Phase: During this phase, the software is developed according to the design specifications. The coding of the software is done, unit testing is performed, and the software components are integrated. The outcome of this phase is the software code that meets the requirements of the software.

Testing Phase: This phase involves testing the software to ensure that it meets the specified requirements and functions correctly. This includes functional testing, system testing, performance testing, and user acceptance testing. The outcome of this phase is a Test Plan document that outlines the test cases, results, and issues.

Deployment Phase: In this phase, the software is deployed to the end-users. This includes installation, configuration, and migration of data from the existing systems to the new software. The outcome of this phase is a Deployment Plan document that outlines the installation, configuration, and migration of data.

Maintenance Phase: This phase involves ongoing support and maintenance of the software to ensure that it continues to function correctly and meet the changing needs of the end-users. This includes fixing defects, making updates and enhancements, and providing technical support. The outcome of this phase is a Maintenance Plan document that outlines the ongoing support and maintenance of the software.

what is Continuous Integration , Continuous Deployment , Continuous Delivery ?


Continuous Integration (CI), Continuous Deployment (CD), and Continuous Delivery (CD) are all practices that are commonly used in software development. While these terms are often used interchangeably, they refer to different aspects of the software development process.

Continuous Integration (CI) is a practice where developers integrate their code changes into a shared repository on a regular basis. Each time a change is made, a build is automatically triggered, and the code is tested to ensure that it integrates successfully with the rest of the codebase. The goal of CI is to catch integration problems early in the development process, reducing the time and effort required to fix them.

Continuous Deployment (CD) is a practice where every code change that passes the automated tests is automatically deployed to production. The goal of CD is to reduce the time between the development of a feature and its deployment to production, resulting in faster feedback and shorter development cycles.

Continuous Delivery (CD) is a practice where code changes are automatically built, tested, and prepared for release to production. While the release to production is not automatic, the process of preparing the release is automated, resulting in a faster and more reliable release process.

Why only Jenkins?
 It has so many plug-ins.
 You can write your own plug-in
 You can use community plug-ins
 Jenkins is not just a tool. It is a framework. I.e. you can do what ever you 
want. All you need is plug-ins.
 We can attach slaves (nodes) to Jenkins master. It instructs others 
(slaves) to do Job. If slaves are not available,
 Jenkins itself does the job.
 Jenkins also acts as crone server replacement. I.e. can do repeated tasks 
automatically
 Running some scripts regularly
 E.g.: Automatic daily alarm.
 Can create Labels (Group of slaves) (Can restrict where the project has to 
run

What is Jenkins Architecture?
Jenkins architecture is Client-Server model. Where ever, we install Jenkins, we 
call that server is Jenkins master. We can create slaves also in Jenkins, so that, 
server load will be distributed to slaves. Jenkins master randomly assigns tasks 
to slaves. But if you want to restrict any job to run in particular slave, then we 
can do it so that, that particular job will be executed in that slave only. We can 
group some slaves by using “Label”

How many types of configurations in Jenkins?
There are total 3 types of configurations in Jenkins.
1. Global: – Here, whatever configuration changes we do, applicable to whole 
Jenkins including jobs as well as nodes. This configuration has high priority.
2. Job: – These configurations applicable to only Jobs. Jobs also we call as 
projects or items in Jenkins.
3. Node: – These configurations applicable to only nodes. Also we call Slaves. 
These are kind of helpers to Jenkins master to distribute the excessive load.

What do you mean by workspace in Jenkins?
The workspace is the location on your computer where Jenkins places all files 
related to the Jenkins project. By default each project or job is assigned a 
workspace location and it contains Jenkins-specific project metadata, 
temporary files like logs and any build artifacts, including transient build files. 
Jenkins web page acts like a window through which we are actually doing work 
in workspace.

what is pluging  ?
Plugins are software components in Jenkins that add new functionality or enhance existing features of the Jenkins automation server. They are written in Java and can be installed in Jenkins to extend its capabilities and integrate with external tools and technologies.
(use plugings to extened functionality of jenkins.)



















======================================================================================================================================================================
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
 
 
 
 
 
 
 
 
 
 
