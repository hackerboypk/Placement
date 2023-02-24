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










 
  
