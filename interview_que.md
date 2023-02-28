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

The Amazon Web Services Identity and Access Management service is like a security guard at the door to Amazon Web Services. 
This is where Aws Services and its environment are authenticated and authorized. 
The basic building blocks of AWS IAM are IAM roles, IAM users, groups and policies. 

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

uses of roles?]
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

Launch Templet.?
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
 
  
