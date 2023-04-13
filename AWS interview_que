What is cloud ?
The cloud" refers to servers that are accessed over the Internet, and the software and databases that run on those servers.
Cloud servers are located in data centers all over the world.
By using cloud computing, users and companies do not have to manage physical servers themselves or run software applications on their own machines.

what is cloud computing?
Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing.
Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services,
such as computing power, storage, and databases, on an as-needed basis from a cloud provider like Amazon Web Services (AWS).

                 On Premises	                                                  On Cloud
1.	Control of user is more.	                                    Control of user is less as third parties are involved.
2.	Infrastructure is not easy to scale.	                        Infrastructure is easy to scale.
3.	Internet connectivity is not need all the time.	              Internet is must for the services of the cloud.
4.	These services run within the enterprise only.	              The services of cloud depends on the third parties so these are not only accessed within the enterprise.
5.	These services are not quite flexible.	                      The services of cloud are highly flexible.
6.	Not available on a subscription basis.	                      Services are available for purchase.
7.	For hardware and software updates, enterprise is responsible.	For hardware and software updates, third party is responsible.
8.	Cost is fixed.	                                              Cost is not fixed, as additional services comes with additional charges.
9.	Data is easily portable.	                                    Data is not easily portable.
10.	The deployment happens in the local environment.	            The deployment happens on the internet.
11.	Security is more.	                                            Security is less as all the information is stored in the cloud.
12.	These services are used in large companies.	                  These services are used in small and mid sized companies.
13.	Implementation time is more.	                                Implementation time is less.

Deployment Model of cloud
Different types of cloud computing deployment models are:

    Public cloud 
    Private cloud
    Hybrid cloud
    Community cloud
    Multi-cloud 
  1. Public cloud
 The public cloud makes it possible for anybody to access systems and services. 
 The public cloud may be less secure as it is open to everyone.
 The public cloud is one in which cloud infrastructure services are provided over the internet to the general people or major industry groups.
 This form of cloud computing is an excellent example of cloud hosting, in which service providers supply services to a variety of customers. In this arrangement, storage backup and retrieval services are given for free, as a subscription, or on a per-user basis. ex. gmail google app engine
 2. Private cloud
The private cloud deployment model is the exact opposite of the public cloud deployment model. It’s a one-on-one environment for a single user (customer). There is no need to share your hardware with anyone else. The distinction between private and public clouds is in how you handle all of the hardware. It is also called the “internal cloud” & it refers to the ability to access systems and services within a given border or organization. 
3. hybrid cloud
By bridging the public and private worlds with a layer of proprietary software, hybrid cloud computing gives the best of both worlds. With a hybrid solution, you may host the app in a safe environment while taking advantage of the public cloud’s cost savings. Organizations can move data and applications between different clouds using a combination of two or more cloud deployment methods, depending on their needs. 
4. community cloud
It allows systems and services to be accessible by a group of organizations. It is a distributed system that is created by integrating the services of different clouds to address the specific needs of a community, industry, or business. The infrastructure of the community could be shared between the organization which has shared concerns or tasks. It is generally managed by a third party or by the combination of one or more organizations in the community. 

Types of cloud computing 
There are three types of cloud computing
 Iaas (infrastructure as service)
 Paas (platform as service)
 Saas (software as service)

1. Iaas (infrastructure as service)
Infrastructure as a Service (IaaS) contains the most basic building blocks for Cloud infrastructure and offers services on tops of it such as renting IT infrastructure (virtual or physical) and networking features.
IaaS mainly includes Cloud-based services on a pay-as-you-go model. A user pays for computing services on IaaS because it is the fundamental platform to build new technologies.
Infrastructure as service contains things as networking, storage, servers, virtualization are managed by cloud providers
and other things need to manage by our own. ex. ec2

2. Paas (Platform as service)
Platform-as-a-service (PaaS) refers to the supply of on-demand tools for developing, testing, delivering, and managing software applications.
PaaS delivers a framework for developers and IT architects to create web or mobile apps that are scalable, without worrying about setting up or managing the underlying infrastructure of servers, storage, network, and databases needed for development. ex. rds

3. Saas (Software as service)
Software-as-a-service (SaaS) is a method for delivering on-demand software applications through Cloud on a subscription basis. A CSP takes care of managing the Cloud infrastructure and offers SaaS applications over the internet to a user that are accessible through a web browser. These applications are also available on multiple devices which can be accessed from anywhere. ex. gmail elastic beanstalk

IAM (Identity and Access Management)
What is AWS IAM? 

AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.

users vs group ?
A user is an AWS identity that represents an individual or application that interacts with AWS resources. Users have a unique name and credentials (such as a password or access keys) that are used to authenticate their access to AWS services. You can create, manage, and delete users in the AWS Management Console, AWS CLI, or AWS SDKs.
A group is a collection of AWS users that have the same permissions to access AWS resources. By creating a group, you can assign permissions to the group, rather than to individual users. This makes it easier to manage access to resources, especially if you have many users who require the same set of permissions. You can add and remove users from a group, and assign policies to control the group's access to resources.



Iam user:
IAM users can be people or applications that interact with the AWS environment services and its resources.
An IAM user is an identity created in AWS to access various AWS resources and services.
A user has permissions associated with it.
The permissions define which actions that user can perform on a specific resource. 

Iam groups:
IAM groups are collections of IAM users.
Users are organized into groups so you can assign permissions in bulk rather than individually for each user.
In addition, permissions are automatically inherited, making it easier to control how resources are accessed within your account.

iam policies:
IAM Policies are how you determine who has access to what resources in your account.
For example, you could allow users access to all Amazon EC2 instances within your AWS account, or just a specified instance.

Types of iam policies:
Identity-based policies: 
This is the policy that binds with AWS identities, such as a users, group, or role.
IAM policies are an example of that. These policies can be either Amazon Web Services managed or customer-managed.  

Resource-based policies:
AWS resource-based policies are the ones that can be tied directly to Amazon Resources like a bucket policy (S3).
Resource-based policies are only available for certain services. 

inline policy:
An inline policy is a policy that's embedded in an IAM identity (a user, group, or role). 
That is, the policy is an inherent part of the identity. 
if the user gets deleted the policy will also deleted.

roles:
An IAM role is a temporary way to access permissions through your identity. 
instead of being uniquely associated with one person, a role is intended to be assumable by anyone who needs it.
Also, a role does not have standard long-term credentials such as a password or access keys associated with it.
Instead, when you assume a role, it provides you with temporary security credentials for your role session.

There are several types of roles in AWS, each designed to serve a specific purpose. Here are some of the most commonly used types of roles in AWS:

    AWS Service Roles: AWS Service Roles are roles that are used by AWS services to access other AWS services. These roles are typically used to enable cross-service access for automation, monitoring, and other tasks.

    IAM Roles: IAM Roles are roles that are used to delegate permissions to IAM users, groups, or roles. IAM roles are often used to provide temporary access to AWS resources for specific tasks or functions.

    Cross-Account Roles: Cross-Account Roles are roles that allow IAM users or AWS services in one AWS account to access resources in another AWS account. These roles are often used in scenarios where multiple AWS accounts are used for different purposes, such as development, testing, and production environments.

    EC2 Instance Roles: EC2 Instance Roles are roles that are assigned to EC2 instances. These roles are used to provide temporary permissions to resources such as S3 buckets and DynamoDB tables.

    Lambda Execution Roles: Lambda Execution Roles are roles that are assigned to AWS Lambda functions. These roles are used to provide permissions to resources such as S3 buckets, DynamoDB tables, and other AWS services.

    Federated Roles: Federated Roles are roles that allow external identities to assume AWS roles. These roles are often used to enable Single Sign-On (SSO) for corporate users who authenticate with their corporate credentials.

uses of roles?
-roles are the secured way to grant permission to entity that we trust.                                             
-it is an IAM identity which we can create in our account that have specific permission
-an IAm role is similar to IAm user.
-roles is an identity with permission policies that determine what the identity can and cannot do in aws.
-however insted of being uniquely associated with one person ,a role is intended to be assumeable by anyone who  needs it.
-it doesnt have standard long-term creadiantials such as password and access key asssociated with it.
-insted when we assume a role ,it provides us with temporary security creadiantials for our role session.

use casses:-
-we can use roles to delegate access to user, application or servicies that we dont noramlly have access to our aws   resources.
-For example, you might want to grant users in your AWS account access to resources they don't usually have, or grant users in one AWS account access to resources in another account. 
Or you might want to allow a mobile app to use AWS resources, but not want to embed AWS keys within the app (where they can be difficult to rotate and where users can potentially extract them). 
Sometimes you want to give AWS access to users who already have identities defined outside of AWS, such as in your corporate directory. Or, 
you might want to grant access to your account to third parties so that they can perform an audit on your resources.

For these scenarios, you can delegate access to AWS resources using an IAM role. This section introduces roles and the different ways you can use them, 
when and how to choose among approaches, and how to create, manage, switch to (or assume), and delete roles.

what is trust relationship in roles?
->in trust relationship we specify acc id or whom we are allowing to use our resource  on which we are trusting.
Uses of Roles?
-An IAM user in the same AWS account as the role
-An IAM user in a different AWS account than the role
-A web service offered by AWS such as Amazon Elastic Compute Cloud (Amazon EC2)
-An external user authenticated by an external identity provider (IdP) service that is compatible with SAML 2.0 or   OpenID Connect, or a custom-built identity broker.

What is MFA in AWS IAM? 

Multi-factor authentication (MFA) adds an extra layer of security for users accessing AWS resources. In addition to a username and password, an MFA-enabled user must provide a one-time code generated by an authenticator app or sent via SMS or voice call before gaining access. An MFA device can be enabled on your computer, phone, or tablet. 

key features of AWS IAM? 

    Access control to AWS resources 
    Multi-factor authentication (MFA) 
    Federated access 
    Analytics 
    
real time use of identity providers?
-with help of identity provider we can manage our user identities outside of aws and give these user identies permission to use aws resources in your account.
-IDP allow us to manage user identities outside of aws insted of creating IAM user in our aws account.
-this is useful if our organizaton already has its own identity system such as corporate directory
  (Every organization has a corporate directory where employees can quickly locate, view and obtain contact information relating to their coworkers)
-external user sign in on through a well known idp, such as login with amazon,facebook or google .
  we can give those external identities permission to use aws resources in our acc.
-IAM support IDP that are compatible with,
 =openID conect / web identity dedration
 =SAML 2.0 (security acceration markup language)

OPENID CONNECT:
-OpenId connect is an open standard for authentication that is supported by a number of login provider.
-Amazon cognito supports linking of identities with OpenID connect providers that are configured through aws IAM.

SAML 2.0 :
-An IAM SAML 2.0 identity provider is an entity in iam that describes an external identity service that support that SAML 2.0 standard.
-the role permits your orginization IDP to request temporary security crediantials for access to AWS.

benifits of  asume role? how to setup assume role ?
An assume role offers the following advantages:
Temporary credentials
    You can use an assume role and generate temporary security credentials to access the Amazon S3 resources. 
Enhanced security
    You can access Amazon S3 resources by using temporary session credentials. You can request the temporary credentials from the AWS Security Token Service (STS). The process of fetching temporary credentials is secure and transparent. 
User Configurations
    You have the option to specify an appropriate session time for the credentials in the Amazon S3 and Amazon Redshift connectors. AWS STS returns the temporary credentials with a default session time. The credentials expire after crossing the time limit. 
   
================================================================================================================
S3 (simple Storage Service)
What is AWS S3?
Amazon S3 (Simple Storage Service) provides an object storage, which is designed for storing and recovering an arbitrary amount of information or data from anywhere over the internet.
This storage is provided through a web services interface. It offers 99.999999999% durability and 99.99% availability of objects.
It can also store computer files up to 5 terabytes in size.

benefits of AWS Simple Storage Service?
Durability: It gives 99.999999999 percent SLA.
Cheaper: It supports a variety of storage classes. They range from those files that need to be accessed more frequently, like caching, to files that rarely change, like snapshots.
Scalability: Storage resources can be easily scaled up or down based on your organization’s needs.
Availability: The availability of objects on S3 is 99.99 percent
Security: It offers a robust suite of tools for access management and encryption that provide enhanced security.
Flexibility: The Simple Storage Service is perfect for a wide range of uses, including data storage, backups, software delivery, archiving, disaster recovery, hosting websites, mobile applications, IoT devices, and much more.

S3 Versioning?
The Amazon S3 Versioning feature allows you to keep multiple variants of the same object in the same bucket. 
Objects stored in S3 buckets can be preserved, retrieved, and restored with Simple Storage Service Versioning.
It is easy to recover from both unintentional user actions and application failures.

What is Bucket Policy?
Bucket policies allow you to grant access permissions to objects within your bucket by using AWS IAM policies.
A bucket policy can only be associated with the bucket owner. 
An owner of a bucket can assign permissions to any object in the bucket that is attached to the bucket.

What is Access control lists (ACLs) ?
The ACL allows you to grant read-only and write-only access to individual buckets and objects to authorized users.
ACLs are attached to buckets and objects as sub-resources.
ACLs are an older access control system for defining the which AWS accounts or groups are granted access and the type of access.

How large can a Simple Storage Service bucket be?
You can store an unlimited amount of data and objects in an Simple Storage Service bucket.
The size of a single Amazon S3 object can range from 0 bytes to 5 terabytes.
An object of around 5 GB can be uploaded in a single upload request but Multipart Upload must be enabled.

benefits of S3 versioning.
We can store multiple variants of an object in a bucket by versioning it.
An object can be restored to a previous or specific version by versioning.
If an object is deleted or accidentally overwritten, versioning can be used to recover it.

How to configure S3 Versioning on a Bucket?

Versioning helps you keep multiple versions of an object in one place. Follow these steps to enable versioning on an S3 bucket.

    Login to your AWS account.
    Choose Simple Storage Service service.
    Choose a bucket for which versioning should be enabled.
    Go to the properties tab.
    Select versioning from properties.
    Click on the OK button to enable versioning.

diff type of storage in AWS?
->S3 (SIMPLE STORAGE SERVICE)
->EFS (Elastic file System)
->EBS (Elastic block Storage)
-> S3-Glacier
->Storage Gateway
->AWS Elastic Disaster Recovery
->FSx
->AWS Backup
->Snowball (portable storage, use for data migration)

EBS  vs S3 vs EFS

EBS                                                           S3                                                                EFS
-it is block storage ,data stored in unique blocks   -it is object storage store data in block format.           -it store data in file format
-it must attached to EC2 instance                    -can access data by API calls which having protocols        -we can share file in n/w or can mount                                                                                                                          it to diffrent ec2
-provide persisten storage                           -provide unlimited space                                    -we can use it as centralized storage also
-Ex: Unix,ZFS,Ext4                                   -can store backup ,log-file and arcives                      -shared access to files
-provide low latency                                 -have verion control system                                  -web serving
-provide bootable type volume                        -highly avaliable in region
-highly avaliable within az

S3 lifecycle?
->what:
     -it is rules, to define actions on S3, to set duration on objects such as transitioning objects to another storage class, archiving them,
       or deleting them after a specific period of time
      #-we use s3 lifecycle rule for cost optimization of storage of objects by transitive the object from one storage class to another storage class after particular period of time,and gets deleted once it is no longer needed.
->why: 
    -we use lifecycle for Cost optimization
->how:
    -their are three category 
      i)frequent access ii)infrequent access iii)archive
    -these three category are catogorized  in total 7 storage classes:
	Amazon S3 Standard: 
	Amazon S3 Intelligent-Tiering: 
	Amazon S3 Standard Infrequent Access (S3 Standard-IA): 
	Amazon S3 One Zone-Infrequent Access (S3 One Zone-IA): 
	Amazon S3 Glacier Instant Retrival: 
  Amazon S3 Glacier flexible Retrival: 
	Amazon S3 Glacier Deep Archive

->can take the option life Cycle. Rule, on the management section, of the bucket.

->we have to  maintain transition like std. to std IA or 1 zone IA or glacier 
in which we have to specify min. days of time 
like to transit Std. to std IA it takes min. 30 days and glac. to Deep Glac. 
it is about min. 90 days. 

Object Lock
When enabled, this object will be prevented from being deleted or overwritten until the hold is explicitly removed.
Store objects using a write-once-read-many (WORM) model to help you prevent objects from being deleted or overwritten for a fixed amount of time or indefinitely. 

Server-side encryption with Amazon S3 managed keys (SSE-S3)
is the base level of encryption setting of new objects that are uploaded to an S3 bucket.
You can configure your object encryption by using either server-side encryption with Amazon S3 managed keys (SSE-S3) (the default) or server-side encryption with AWS Key Management Service (AWS KMS) keys (SSE-KMS)

============================================================================================

EC2 (elestic conpute cloud)
What is Virtualization? 
.Virtualization is technology that you can use to create virtual representations of servers, storage, networks, and other physical machines.
.Virtualization is a process that allows a computer to share its hardware resources with multiple digitally separated environments.
Each virtualized environment runs within its allocated resources, such as memory, processing power, and storage. 
.virtulization is technology that allows us to create multiple simulated enviorment or dedicated  resources from a single ,physical hardware system.
s/w called a hypervisor connects directly to that h/w and allow us to split 1 system into sepreate,distinct and  secure enviorment know as vm

Virtualization vs Cloud ?

	Cloud							Virtualization
1.cloud is higly scalable				1.virtulization is low scalable
2.it is flexible					2.it is less fexible
3.in cc work load is stateless				3.in vz workoad is stateful.
4.cost is higher than vz				4.cheaper than cc
5.it require many dedicated h/w 			5. it require single dedicated h/w
6.cc provides unnlimited space 				6.storage space depends on physical server capacity in vz
7.cc is of two type :public and private			7.vz is of two type :hardware vz and application vz.
8.it is template based 					8. it is image based
9. IAAS type						9. PAAS type

What is hypervisor ?
A hypervisor is computer software or hardware that enables you to host multiple virtual machines.
it contains two types
type1 called as bare metal hypervisor directly on h/w
type2 called as hosted hypervisor it required os 

what is ec2 ?
Amazon Elastic Compute Cloud is  cloud-computing platform,  that allows users to rent virtual computers on which to run their own computer applications
Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) Cloud.
Using Amazon EC2 eliminates your need to invest in hardware up front, so you can develop and deploy applications faster. 
You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage.

Features of Amazon EC2
Amazon EC2 provides the following features:
Virtual computing environments, known as instances
Preconfigured templates for your instances, known as Amazon Machine Images (AMIs),
Various configurations of CPU, memory, storage, and networking capacity for your instances, known as instance types
Secure login information for your instances using key pairs (AWS stores the public key, and you store the private key in a secure place)
Storage volumes for temporary data that's deleted when you stop, hibernate, or terminate your instance, known as instance store volumes
Persistent storage volumes for your data using Amazon Elastic Block Store (Amazon EBS), known as Amazon EBS volumes
Multiple physical locations for your resources, such as instances and Amazon EBS volumes, known as Regions and Availability Zones
A firewall that enables you to specify the protocols, ports, and source IP ranges that can reach your instances using security groups
Static IPv4 addresses for dynamic cloud computing, known as Elastic IP addresses
Metadata, known as tags, that you can create and assign to your Amazon EC2 resources
Virtual networks you can create that are logically isolated from the rest of the AWS Cloud, and that you can optionally connect to your own network, known as virtual private clouds (VPCs)

Create Ec2 instance
steps 
ec2>instance>launch instance>instance name>ami>instance type>key pair>network setting>configure storage>advanced details>launch instance
Instance state
1.pending
The instance is preparing to enter the running state. An instance enters the pending state when it launches for the first time, or when it is started after being in the stopped state.
2.running
The instance is running and ready for use.
3.stopping
The instance is preparing to be stopped or stop-hibernated.
4.stopped
The instance is shut down and cannot be used. The instance can be started at any time.
5.shutting-down
The instance is preparing to be terminated.
6.terminated
The instance has been permanently deleted and cannot be started.

Staus check
0/2 h/w issue 
1/2 s/w configuration issue
2/2 all ok

T2 
Instance	vCPU*	CPU Credits    Mem (GiB)        Storage 	    Network Performance
t2.nano		1	3		0.5		EBS-Only	  Low
t2.micro	1	6		1		EBS-Only
Low to Moderate
t2.small	1	12		2		EBS-Only
Low to Moderate
t2.medium	2	24		4		EBS-Only
Low to Moderate
t2.large	2	36		8		EBS-Only	Low to Moderate
t2.xlarge	4	54		16		EBS-Only	Moderate
t2.2xlarge	8	81		32		EBS-Only	Moderate
user cases
Websites and web applications, development environments, build servers, code repositories, micro services, test and staging environments, and line of business applications.
M series
Instance Size	vCPU	Memory (GiB)	Instance Storage (GB)	Network Bandwidth (Gbps)***	EBS Bandwidth (Mbps)
m6g.medium	1	4	EBS-Only	Up to 10	Up to 4,750
m6g.large	2	8	EBS-Only	Up to 10	Up to 4,750
m6g.xlarge	4	16	EBS-Only	Up to 10	Up to 4,750
m6g.2xlarge	8	32	EBS-Only	Up to 10	Up to 4,750
m6g.4xlarge	16	64	EBS-Only	Up to 10	4,750

Use Cases

Applications built on open-source software such as application servers, microservices, gaming servers, mid-size data stores, and caching fleets.

Types of intance 
1)Genral Purpose  <M , T> General purpose instances provide a balance of compute, memory and networking resources,
2)computer optmized <C , H> Compute Optimized instances are ideal for compute bound applications that benefit from high performance processors.
3)memory optimized  <R , X> Memory optimized instances are designed to deliver fast performance for workloads that process large data sets in memory.
4)Storage optimized <I,D> Storage optimized instances are designed for workloads that require high, sequential read and write access to very large data sets on local storage.
5)Accelerated computing  Accelerated computing instances use hardware accelerators, or co-processors, to perform functions, such as floating point number calculations, graphics processing, or data pattern matching, more efficiently than is possible in software running on CPUs.


Type of purchasing option 
                                            
1 On-Demand Instances – Pay, by the second, for the instances that you launch.
2 Savings Plans – Reduce your Amazon EC2 costs by making a commitment to a consistent amount of usage, in USD per hour, for a term of 1 or 3 years.
3 Reserved Instances – Reduce your Amazon EC2 costs by making a commitment to a consistent instance configuration, including instance type and Region, for a term of 1 or 3 years.
4 Spot Instances – Request unused EC2 instances, which can reduce your Amazon EC2 costs significantly.
5 Dedicated Hosts – Pay for a physical host that is fully dedicated to running your instances, and bring your existing per-socket, per-core, or per-VM software licenses to reduce costs.
6 Dedicated Instances – Pay, by the hour, for instances that run on single-tenant hardware.
7 Capacity Reservations – Reserve capacity for your EC2 instances in a specific Availability Zone for any duration.					    

What is tenancy. ?

Tenancy defines how EC2 instances are distributed across physical hardware and affects pricing. There are three tenancy options available:
Shared (default) — Multiple AWS accounts may share the same physical hardware.
Dedicated Instance (dedicated) — Your instance runs on single-tenant hardware.
Dedicated Host (host) — Your instance runs on a physical server with EC2 instance capacity fully dedicated to your use, an isolated server with configurations that you can control.

Launch Templete ?
A launch template is similar to a launch configuration, in that it specifies instance configuration information.
It includes the ID of the Amazon Machine Image (AMI), the instance type, a key pair, security groups, and other parameters used to launch EC2 instances.

What is AMI

An Amazon Machine Image (AMI) is a supported and maintained image provided by AWS that provides the information required to launch an instance.
You must specify an AMI when you launch an instance.
You can launch multiple instances from a single AMI when you require multiple instances with the same configuration.
You can use different AMIs to launch instances when you require instances with different configurations.

Volume ?
EBS
An Amazon EBS volume is a durable, block-level storage device that you can attach to your instances.
After you attach a volume to an instance, you can use it as you would use a physical hard drive.
EBS volumes are flexible. 
You can attach multiple EBS volumes to a single instance. 
The volume and instance must be in the same Availability Zone. 

Volume types ?

Solid state drive (SSD) volumes
SSD-backed volumes are optimized for transactional workloads involving frequent read/write operations with small I/O size, where the dominant performance attribute is IOPS. SSD-backed volume types include General Purpose SSD and Provisioned IOPS SSD .

Hard disk drive (HDD) volumes
HDD-backed volumes are optimized for large streaming workloads where the dominant performance attribute is throughput.
HDD volume types include Throughput Optimized HDD and Cold HDD. 

Previous generation volumes
Previous generation volumes are hard disk drives that you can use for workloads with small datasets where data is accessed infrequently and performance is not of primary importance.

what is security group ?
A security group acts as a virtual firewall for your EC2 instances to control incoming and outgoing traffic. Inbound rules control the incoming traffic to your instance, and outbound rules control the outgoing traffic from your instance. When you launch an instance, you can specify one or more security groups.

placement group
A cluster placement group is a logical grouping of instances within a single Availability Zone that benefit from low network latency, high network throughput.

 Key pair. ?
 A key pair is a combination of a public key that is used to encrypt data and a private key that is used to decrypt data. For more information about key pairs, see Amazon EC2 Key Pairs in the Amazon EC2 User Guide for Linux Instances. The AWS CloudFormation template for this tutorial, development-environment.

network interface ?
An elastic network interface is a logical networking component in a VPC that represents a virtual network card. It can include the following attributes: A primary private IPv4 address from the IPv4 address range of your VPC. One or more secondary private IPv4 addresses from the IPv4 address range of your VPC.

Load Balancer:
a load balancer is a service that distributes incoming traffic among multiple EC2 instances in order to improve availability, scalability, and fault tolerance.
types of load balancers for EC2:
    Application Load Balancer (ALB): This type of load balancer is ideal for routing traffic to multiple HTTP/HTTPS servers based on the content of the request. ALBs can route traffic based on URL path, host header, and query string parameters, among other factors. operates at Layer 7.

   Network Load Balancer (NLB): This type of load balancer is designed to handle high levels of traffic and is ideal for TCP and UDP traffic. NLBs can handle millions of requests per second and can route traffic based on IP protocol data. Network Load Balancer (NLB) operates at Layer 4.
   
   Gateway Load Balancer (GWLB) is a service that allows you to route traffic to a specific IP address or port within your VPC (Virtual Private Cloud). GWLB is designed to handle high volumes of external network traffic and provides a scalable, highly available solution for routing traffic to multiple resources such as EC2 instances, container-based applications, and NAT gateways.

GWLB operates at the application layer (Layer 7) of (OSI) model and can route traffic based on a variety of factors such as HTTP headers, source IP addresses, and SSL/TLS certificates.

Both types of load balancers can automatically scale up or down based on the incoming traffic, making them a powerful tool for ensuring high availability and scalability in your AWS EC2 infrastructure.


do it again and solve the errors
==============================================================================================================================
networking
===============================
Computer network :
computer network is interconncection between two or more nodes
An interconnection of multiple devices, also known as hosts, that are connected using multiple paths for the purpose of sending/receiving data or media.
Network Devices: Network devices, also known as networking hardware, are physical devices that allow hardware on a computer network to communicate and interact with one another. For example Repeater, Hub, Bridge, Switch, Routers, Gateway, Brouter, and NIC, etc.
 Repeater – A repeater operates at the physical layer. Its job is to regenerate the signal over the same network before the signal becomes too weak or corrupted to extend the length to which the signal can be transmitted over the same network.
  Hub –  A hub is a basically multi-port repeater. A hub connects multiple wires coming from different branches, for example, the connector in star topology which connects different stations. Hubs cannot filter data, so data packets are sent to all connected devices.  In other words, the collision domain of all hosts connected through Hub remains one.
  Bridge – A bridge operates at the data link layer. A bridge is a repeater, with add on the functionality of filtering content by reading the MAC addresses of the source and destination. It is also used for interconnecting two LANs working on the same protocol.
  A switch is a data link layer device. The switch can perform error checking before forwarding data, which makes it very efficient as it does not forward packets that have errors and forward good packets selectively to the correct port only.
  Routers – A router is a device like a switch that routes data packets based on their IP addresses. The router is mainly a Network Layer device. Routers normally connect LANs and WANs and have a dynamically updating routing table based on which they make decisions on routing the data packets. The router divides the broadcast domains of hosts connected through it.
  Gateway – A gateway, as the name suggests, is a passage to connect two networks that may work upon different networking models. They work as messenger agents that take data from one system, interpret it, and transfer it to another system.
  NIC – NIC or network interface card is a network adapter that is used to connect the computer to the network. It is installed in the computer to establish a LAN.
  
  OSI: 
OSI stands for Open Systems Interconnection. It is a reference model that specifies standards for communications protocols and also the functionalities of each layer. The OSI has been developed by the International Organization For Standardization and it is 7 layer architecture. Each layer of OSI has different functions and each layer has to follow different protocols.
The 7 layers are:-

physical layer:- bits, 0,1(binary) digital data, wired or wireless sending
Data link layer: framing of data, data flow control, physical addressing, mac address
Network layer: convert data into packets, store ip of sender and reciver, routing
Transport layer: segmentation of data, tcp and udp
Session layer: start session between sender and reciver, it has ability to resume sending data if connection lost
Presentation layer: formatting of data, encryption,decription, compression, decompressiton
Application layer: app, browser

types of ip 
===============================================================================================================================================================
VPC

what is vpc ?
VPC stands for Virtual Private Cloud, which is a virtual network environment that allows you to provision and manage virtual private networks (VPNs) in the cloud. It provides a secure and isolated environment within a public cloud infrastructure, such as Amazon Web Services (AWS).

diff between default vpc and custom vpc

Default vpc										
Every AWS account comes with a default VPC, which is preconfigured and ready to use. 
The default VPC is designed to make it easy to get started with AWS by providing a VPC that has a set of default configurations
The default VPC has a CIDR block of 172.31.0.0/16, which provides up to 65,536 private IP addresses.
By default, all the subnets in the default VPC are configured to use the Internet Gateway (IGW) to provide internet access to the instances running in the VPC.

Custom VPC: 
A custom VPC is a VPC that you create and configure based on your specific requirements.
When you create a custom VPC, you have complete control over the VPC's network configuration, including the IP address range, subnets, routing tables, security settings, and more.
With a custom VPC, you can create multiple subnets, each with its own IP address range, and configure the network routing between the subnets.
You can also configure network access control lists (ACLs) and security groups to control traffic to and from the instances running in the VPC.
A custom VPC can be created and managed using the AWS Management Console, AWS CLI, or AWS SDKs.

Features of vpc

1. Isolation: VPCs provide logical isolation of resources, which means you can launch resources like EC2 instances, RDS databases, and ELBs in a private and secure network.
2. Control: You have complete control over the IP address range, subnets, and routing tables for your VPC.
3. Security: VPCs allow you to configure security groups, network ACLs, and other network security features to protect your resources from unauthorized access.
4. Scalability: VPCs can be scaled easily by adding or removing subnets, changing routing tables, and launching new instances.
5. Compatibility: VPCs are compatible with other AWS services like Direct Connect, VPN, and Elastic Load Balancing, which makes it easier to integrate your VPC with your existing infrastructure.
6. Flexibility: VPCs allow you to customize your network topology, which means you can create a network that suits your specific needs.
7. Cost-effectiveness: VPCs are charged on a pay-as-you-go basis, which means you only pay for the resources you use.

Components of vpc
A Virtual Private Cloud (VPC) is a virtual network infrastructure that provides a private, isolated environment for running your resources in the cloud. The components of a VPC typically include:
1. Subnets: Subnets are network segments within a VPC that are used to organize resources and control network traffic. Each subnet is associated with a particular availability zone and can be configured with its own routing table and network access control list (ACL).
2. Route Tables: Route tables are used to determine how network traffic is directed within the VPC. Each subnet is associated with a route table, which specifies the destination for traffic that originates from that subnet.
3. Security Groups: Security groups are used to control access to resources within the VPC. They act as virtual firewalls, allowing or denying traffic based on defined rules.
4. Network ACLs: Network access control lists (ACLs) are used to control traffic between subnets in the VPC. They operate at the subnet level and can be used to allow or deny traffic based on IP addresses, ports, and protocols.
5. Internet Gateway: An internet gateway is used to allow resources within the VPC to communicate with the internet. It provides a route for traffic to flow between the VPC and the public internet.
6. NAT Gateway: A network address translation (NAT) gateway is used to allow resources within a private subnet to access the internet. It provides a way to translate private IP addresses to public IP addresses and vice versa.
7. VPC Endpoints: VPC endpoints allow resources within a VPC to access AWS services without the need for internet gateways or NAT gateways. They provide a secure and private connection to AWS services.
These are some of the core components of a VPC, but there are also other features such as VPC peering, VPN connections, and Direct Connect that can be used to further enhance the functionality and security of your VPC.

how many subnets can be created in vpc
you can create up to 200 subnets per VPC, but this limit can be increased by submitting a support request to AWS.

how many route tables can be created in vpc 
 In general, the default limit for the number of route tables that can be created per VPC is 200, but this limit can be increased by submitting a support request to AWS.
 
route table vs main route table

The main difference between a route table and a main route table in a VPC is that the main route table is the default route table that is automatically created when you create a new VPC.
custom route table : A route table that you create for your VPC.
By default, the main route table has a higher priority than any additional route tables that you create in the VPC.
The main route table cannot be deleted, but it can be modified like any other route table.
The main route table is associated with the VPC's internet gateway, which allows resources within the VPC to communicate with the public internet. 
Additional route tables must be explicitly configured with their own internet gateway if they need to access the internet.


 DHCP (Dynamic Host Configuration Protocol) is a network protocol used to automatically assign IP addresses and other network configuration settings to devices on a network. In AWS, DHCP is used to assign IP addresses and other configuration settings to instances running in a VPC.
 
 Different  security groups and nacl 
 
 security groups :- it is the first layer of defense .it adds a security to ec2 intance that control both inbound and outbound traffic at the intance level
 
 Nacl (Network access control list)
 It is the secound layer of defense .It also add on additional layer of security associated with subnet that control both inbound and outbound traffic at the subnet level 
 
 Peering connections
Use a VPC peering connection to route traffic between the resources in two VPCs.
VPC peering is a private connection between VPCs, and traffic between the two VPCs never leaves the AWS network. This makes VPC peering a secure way to connect VPCs without exposing traffic to the public internet.

VPC peering between two VPCs, follow these steps:

1. Create a VPC peering connection: To create a VPC peering connection, you need to have control over both VPCs and each VPC must have a unique CIDR block. You also need to know the VPC ID of each VPC. Go to the Amazon VPC console, choose the VPC peering connections option, and click on the "Create Peering Connection" button. Specify the VPC ID of the VPC you want to peer with, as well as the peering connection name.

2.Accept the VPC peering connection: The owner of the other VPC will receive a request to accept the VPC peering connection. Once they accept the request, the VPC peering connection is established, and traffic can flow between the two VPCs.

3.Configure route tables: By default, VPC peering connections do not have routes associated with them. You need to configure the route tables of each VPC to route traffic to the other VPC through the VPC peering connection. Go to the Amazon VPC console, choose the route tables option, and add a new route to the VPC peering connection.

4.Allow traffic through network ACLs and security groups: If you have network ACLs or security groups configured on the VPCs, you need to allow traffic from the other VPC through them. For example, if you have a security group that only allows traffic from specific IP addresses, you need to add the IP addresses of the other VPC to the security group.
 
 Transit Gateway:-
 
 A Transit Gateway acts as a hub for connecting multiple VPCs and on-premises networks. Instead of creating separate peering connections between each VPC and on-premises network, you can create a single connection to the Transit Gateway. This can greatly simplify network architecture and reduce the number of connections you need to manage.
 
 step of Transit Gateway

1.Create a Transit Gateway: Go to the Amazon VPC console, choose the Transit Gateways option, and click on the "Create Transit Gateway" button. Specify a name for the Transit Gateway, as well as any optional settings.

2.Attach VPCs: Once the Transit Gateway is created, you can attach VPCs to it. Go to the Transit Gateway attachments option, and click on the "Create Transit Gateway Attachment" button. Select the VPC you want to attach to the Transit Gateway, as well as the attachment type (either VPC or VPN).

3.Configure routing: By default, Transit Gateways do not have routes associated with them. You need to configure the route tables of each VPC to route traffic to the Transit Gateway. Go to the Amazon VPC console, choose the route tables option, and add a new route to the Transit Gateway attachment.

4.Create and attach VPN connections (if needed): If you need to connect on-premises networks to the Transit Gateway, you can create and attach VPN connections. Go to the Amazon VPC console, choose the VPN connections option, and click on the "Create VPN Connection" button. Specify the VPN connection details, and attach it to the Transit Gateway.

5.Configure security groups and network ACLs (if needed): If you have security groups or network ACLs configured on the VPCs, you need to allow traffic from the other VPCs and on-premises networks through them. For example, if you have a security group that only allows traffic from specific IP addresses, you need to add the IP addresses of the other VPCs and on-premises networks to the security group.

VPC peering and transit gateway are two options for connecting multiple VPCs within AWS, but they differ in their capabilities and use cases.

VPC peering is a way to connect two VPCs together so that they can communicate with each other over a private network. VPC peering is ideal for scenarios where you need to connect VPCs within the same AWS region, as it provides low-latency, high-bandwidth connectivity. However, VPC peering is not transitive, meaning that if you want to connect more than two VPCs, you will need to create separate peering connections between each pair of VPCs. This can become complex and difficult to manage as the number of VPCs increases.

Transit gateway, on the other hand, is a fully-managed service that allows you to connect multiple VPCs and on-premises networks together in a hub-and-spoke model. Transit gateway provides a central hub that simplifies network management by allowing you to centrally manage routing and security policies across all of your connected networks. Transit gateway is ideal for scenarios where you need to connect multiple VPCs across different AWS regions or with on-premises networks. Transit gateway is also transitive, meaning that traffic can be routed between multiple VPCs through the transit gateway.

================================================================================================================================================================
RDS...

What is RDS ?
RDS stands for "Relational Database Service." It is a web service provided by Amazon Web Services (AWS) that makes it easy to set up, operate, and scale a relational database in the cloud.

data engines in rds ?

MySQL: An open-source relational database management system (RDBMS) that is widely used in web applications. RDS for MySQL provides scalable, highly available, and fully managed MySQL instances.

PostgreSQL: An open-source object-relational database management system (ORDBMS) that is known for its powerful features and reliability. RDS for PostgreSQL provides scalable, highly available, and fully managed PostgreSQL instances.

Oracle: A commercial relational database management system that is widely used in enterprise applications. RDS for Oracle provides scalable, highly available, and fully managed Oracle instances.

SQL Server: A commercial relational database management system that is widely used in enterprise applications. RDS for SQL Server provides scalable, highly available, and fully managed SQL Server instances.

Amazon Aurora: A cloud-native relational database engine that is designed for high performance, scalability, and availability. Aurora is compatible with both MySQL and PostgreSQL, and provides features such as automatic scaling, fault tolerance, and self-healing.

MariaDB: A community-developed fork of MySQL that provides enhanced performance, scalability, and reliability.

Nosql vs sql
SQL (Structured Query Language) databases are relational databases that use tables with rows and columns to store data. 
SQL databases are characterized by their ability to handle structured data, which is data that is organized into a predefined structure or schema. 
SQL databases are best suited for applications that require complex transactions, and where data consistency and integrity are critical. 
SQL databases are also ideal for applications that require a high degree of scalability, reliability, and availability.


NoSQL (Not Only SQL) databases, on the other hand, are non-relational databases that store data in a variety of ways, including key-value pairs, document-oriented, column-family, or graph databases. 
NoSQL databases are characterized by their ability to handle unstructured or semi-structured data, which is data that doesn't fit neatly into a predefined schema. NoSQL databases are best suited for applications that require high-speed access to large volumes of data, such as social media platforms, real-time analytics, and content management systems.

what is parameter gropus in rds 
A parameter group in Amazon RDS is a collection of configuration parameters and values that are applied to one or more DB instances. These parameters define the behavior of the database engine and control various settings, such as the size of the buffer pool, the number of connections allowed, and the log retention period.
benfites of parameters gropus flexibility ,consistence ,security ,performance 


To create a cluster in Amazon RDS, you can follow these steps:
Log in to the AWS Management Console and navigate to the Amazon RDS dashboard.
Click on the "Create database" button.
Choose the "Amazon Aurora" engine type.
Choose the edition of Aurora you want to use. You can choose between Aurora with MySQL compatibility or Aurora with PostgreSQL compatibility.
Choose the version of Aurora you want to use.
Select the cluster configuration. You can choose to create a serverless Aurora cluster or a standard Aurora cluster.
Configure the database settings, including the database name, username, and password.
Configure the network settings, including the Virtual Private Cloud (VPC), subnets, and security groups.
Configure the backup and maintenance settings, including the backup retention period and maintenance window.
Review your configuration and click on the "Create database" button.
Wait for the cluster to be created. This may take several minutes.
Once the cluster is created, you can connect to it using a client tool such as MySQL Workbench or pgAdmin. You can also use the AWS Management Console to manage your cluster, including monitoring performance metrics, scaling the cluster, and managing backups and snapshots.

storeage classes in efs 
1.Standard: This is the default storage class and is suitable for general-purpose file storage workloads. It provides low-latency performance and is designed for workloads that require frequent access to files.
2.Infrequent Access (IA): This storage class is suitable for workloads that require less frequent access to files. It provides lower storage costs than the Standard storage class but has slightly higher access latencies.
3.One Zone Infrequent Access (One Zone-IA): This storage class is similar to the IA storage class, but the data is stored in a single availability zone rather than across multiple availability zones. It provides lower storage costs than the IA storage class but has a higher risk of data loss in the event of an availability zone failure.
4.Intelligent-Tiering: This storage class is designed for workloads with changing access patterns. It uses machine learning to automatically move files between the Standard and IA storage classes based on their access patterns. This allows you to optimize your storage costs without having to manually move files between storage classes.
================================================================================================================================
route 53

Amazon Route 53 is a highly available and scalable Domain Name System (DNS) It is used to route internet traffic to resources such as websites, web applications, and other internet-based services.

Route 53 enables you to register domain names, such as example.com, and manage the DNS records associated with those domain names.
It can route requests to resources within AWS, such as Amazon Elastic Compute Cloud (EC2) instances, Amazon Elastic Load Balancing (ELB) load balancers, Amazon Simple Storage Service (S3) buckets, and other AWS resources.
It can also route requests to resources outside of AWS, such as endpoints hosted in your own data center or other third-party services.

Route 53 provides a range of features, including traffic management, health checks, and DNS failover. These features help to ensure high availability, reliability, and scalability of your applications and services.

Record types in route 53
Route 53 supports several types of DNS resource records that can be used to manage your DNS configuration. Some of the most commonly used record types in Route 53 include:
A Record (Address Record): Maps a domain name to an IPv4 address.
AAAA Record (IPv6 Address Record): Maps a domain name to an IPv6 address.
CNAME Record (Canonical Name Record): Creates an alias for a domain name that points to another domain name.
MX Record (Mail Exchange Record): Specifies the mail servers that are responsible for accepting email messages on behalf of a domain.
NS Record (Name Server Record): Specifies the authoritative name servers for a domain.
SOA Record (Start of Authority Record): Specifies the authoritative name server for a DNS zone and provides other information about the zone.
SRV Record (Service Record): Specifies the location of a service on the internet.
TXT Record (Text Record): Stores arbitrary text data associated with a domain name.
Route 53 also supports several other record types that are less commonly used, such as PTR records for reverse DNS lookups, SPF records for email authentication, and NAPTR records for advanced service discovery.
 
 routing policies in route 53
 The available routing policies in Route 53 include:
1.Simple Routing: This routing policy is used to route traffic to a single resource that is specified by an A record or a CNAME record.
2.Weighted Routing: This routing policy is used to distribute traffic among multiple resources based on the weights assigned to each resource. The weights are specified as a percentage, and Route 53 will route traffic based on those percentages.
3.Latency-based Routing: This routing policy is used to route traffic to the resource that has the lowest latency (i.e., the resource that is geographically closest to the client making the DNS query).
4.Failover Routing: This routing policy is used to route traffic to a secondary resource (such as a backup server) if the primary resource is unavailable.
5.Geolocation Routing: This routing policy is used to route traffic based on the geographic location of the client making the DNS query.
6.Multi-value Answer Routing: This routing policy is used to return multiple values (such as multiple IP addresses) for a single DNS query. The order of the values is randomized, which can help to distribute traffic among multiple resources.

what is hosted zone ?
A hosted zone in Amazon Route 53 is a container for the DNS records that define how internet traffic is routed for a specific domain, such as example.com. In other words, it's a collection of DNS records that Route 53 uses to respond to DNS queries for a particular domain.

health check in route 53 
Amazon Route 53 provides a Health Check feature that can be used to monitor the health and availability of your resources such as web servers, load balancers, and other endpoints. A health check in Route 53 periodically sends requests to the resource to verify that it is responding properly, and reports the status of the resource based on the responses received.
There are several types of health checks available in Route 53, including HTTP, HTTPS, TCP, and SSL. Each health check type can be configured with specific settings, such as the request interval, timeout, and the number of failures required to mark the resource as unhealthy.
Once a health check is configured, you can associate it with one or more records in your hosted zone. Route 53 can then use the health check status to control the routing of traffic to the associated resources.

what is ttl ?
TTL stands for "Time to Live," and it is a setting that determines how long DNS (Domain Name System) information is cached by resolvers, including web browsers and Internet service providers (ISPs). In Route 53, TTL can be set for individual DNS records or for entire hosted zones.

extra bonus question
How do you troubleshoot DNS resolution issues in Route 53?
DNS resolution issues in Route 53 can be caused by a variety of factors, including misconfigured DNS records, incorrect DNS settings, or issues with the DNS server or resolver. Here are some steps you can take to troubleshoot DNS resolution issues in Route 53:
Verify the DNS records: Check the DNS records in your hosted zone to ensure that they are correct and up to date. Make sure that the record names and values are accurate and that the TTL settings are appropriate.
Check the DNS settings: Ensure that your DNS settings are correct and that your DNS resolver is pointing to the correct name servers. You can do this by checking your DNS configuration in your domain registrar's control panel.
Use DNS troubleshooting tools: There are several DNS troubleshooting tools you can use to diagnose DNS resolution issues, including dig, nslookup, and traceroute. These tools can help you identify issues with DNS configuration, name server connectivity, and routing.
Check the health of your DNS servers: Use Route 53 Health Checks to monitor the health of your DNS servers and ensure that they are responding correctly. You can also use CloudWatch metrics to monitor the performance of your DNS infrastructure.
Review the DNS resolver cache: DNS resolver caches can sometimes become corrupted or stale, which can cause DNS resolution issues. You can clear the DNS cache on your computer or network to ensure that you are getting the most up-to-date DNS information.
Contact AWS support: If you are unable to resolve the issue using the above steps, you can contact AWS support for further assistance. They can help you diagnose and resolve any DNS resolution issues in your Route 53 configuration.





==========================================================================
