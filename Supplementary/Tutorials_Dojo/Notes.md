# Tutorial Dojo AWS Cloud Practitioner Essentials

## Section 1 -- Introduction to Amazon Web Services

While companies are generally moving towards the cloud, it's still sometimes necessary to store resources on-premises for legacy or regulatory reasons.

## Section 2 -- Compute in the Cloud

Amazon EC2 instances types are optimized for different tasks.

**General purpose** -- Provide a balance of compute, memory, and netwroking resources. Useful for general web applications and small to medium databases.

**Compute optimized** -- Ideal for compute-bound applications that benefit from high-performance processors usuch as dedicated gaming servers.

**Memory optimized** -- Designed to deliver fast performance for workloads that hold large datasets in memory.

Ideal for a high-performance database or a workload that involves processing large amounts of unstructured data.

**Accelerated computing** -- Use hardware accelerators or coprocessors to perform some functions more efficiently than is possible in software running on CPUs.

Ideal for workloads such as graphic applications, game streaming, and application streaming.

**Storage optimized** -- Designed for workloads that require high, sequential read and write access to large datasets on local storage.

Ideal for distributed file systems, data warehousing applications, and high-frequency online transaction processing (OLTP) systems.

### Auto Scaling

Within Amazon EC2 Auto Scaling there are two different approaches:

1. Dynamic scaling -- Scale by responding to changing demand
1. Predictive scaling -- Scale by automatically scheduling the right number of EC2 instances based on predicted demand.

It's also possible to use both dynamic and predictive scaling together for maximal efficiency.

### Monolithic vs Microservice Applications

Applications with tightly coupled components are called monolithic applications.

In a monolithic application, if a single component fails then other components are likely to fail, and it's even possible the entire application fails.

In an application architected with a microservices approach, components are loosely coupled.

## Section 3 -- Global Infrastructure & Reliability

### AWS Regions

Four factors to consider when choosing which region to operate out of include: compliance, proximity, feature availability, and pricing.

### Availability Zones

AWS calls a single data center or a group of data centers an availability zone.

A best practice within AWS is to always run across at least two availability zones in a region.

### Amazon CloudFront

Amazon CloudFront is AWS's CDN, and it works by using edge locations around the world to more quickly deliver content to users.

## Section 4 -- Networking

A networking service we can use to establish boundaries around our AWS resources is an Amazon Virtual Private Cloud (Amazon VPC).

Within a VPC we can organize our resources into subnets. A subnet is a section of a VPC that can contain resources such as Amazon EC2 instances.

To allow public traffic from the internet to access our VPC we must attach an internet gateway to the VPC.

An internet gateway is a connection between a VPC and the internet.

To access private resources in a VPC we can use a virtual private gateway.

AWS Direct Connect is a service that enables us to establish a dedicated private connection between our data center and a VPC.

The VPC component that checks packet permissions for subnets is a network access control list (ACL).

A network ACL is a virtual firewall that controls inbound and outbound traffic at the subnet level.

Networks ACLs perform stateless packet filtering. They remember nothing and check packets that cross the subnet border each way: inbound and outbound.

Security groups on the other hand perform stateful packet filtering -- they remember previous decisions made for incoming packets.

### Domain Name System (DNS)

We can think of DNS as being the phone book of the internet and DNS resolution as being the process of translating a domain name into an IP address.

## Section 5 -- Storage & Databases

### Instance Store

An instance store provides temporary block-level storage for an Amazon EC2 instance.

When the EC2 instance is terminated, any data inside of the instance store is lost.

### Amazon Elastic Block Store (Amazon EBS)

Amazon EBS is a service that provides block-level storage values that can be used with EC2 instances.

If you stop or terminate an EC2 instance, the data on the attached EBS volume still remains available.

We can take incremental backups of EBS volumes by creating Amazon EBS snapshots.

EBS snapshots are incremental backups.

This means that the first backup taken of a volume copies all of the data, while in subsequent backups only the blocks of data that have changed since the most recent snapshot are saved.

### Amazon Simple Storage Service (S3)

In object storage, each object consists of data, metadata, and a key.

Object storage differs from block storage in that when a file in object storage is modified the entire object is updated.

Amazon S3 is a service that provides object-level storage.

### Amazon Elastic File System (Amazon EFS)

In file storage, multiple clients (such as users, applications, servers, etc) can access data that is stored in shared file folders.

File storage is ideal for use cases in which a large number of services and resources need to access the same data at the same time.

Amazon EFS is a scalable file system used with AWS Cloud services and on-premises resources.

## Amazon Relational Database Service (Amazon RDS)

In relational databases data is stored in a way that relates it to other pieces of data.

Relational databases use structured query language (SQL) to store and query data.

Amazon RDS is a service that enables us to run relational databases in the AWS Cloud.

Amazon RDS is supported and can be used along with: Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle Database, Microsoft SQL Server.

Amazon Aurora is an enterprise-class relational database that can help to reduce database costs by reducing unnecessary input/output (I/O) operations while ensuring our database resources remain reliable and available.

### Amazon DynamoDB

Amazon DynamoDB is a nonrelational/NoSQL database that delivers single-digit millisecond performance at any scale.

### Amazon Redshift

Amazon Redshift is a data warehousing service that we can use for big data analytics.

### AWS Database Migration Service

AWS DMS allows us to move data between a source database and a target database.

The source and target databases can be of the same type or different types.

## Section 6 -- Security

### AWS Shared Responsibility Model

Customers are responsible for patching the operating systems and software that run on EC2 instances.

### User Permissions and Access

By default when we create a new IAM user in AWS it has no permissions associated with it.

The security principle of least privilege states that we should not grant more permissions than a user or role actually needs to perform their tasks.

IAM Roles are ideal for situations in which access to services or resources needs to be granted temporarily instead of long-term.

MFA can be enabled for both the root user as well as any and all IAM users.

### AWS Organizations

Service control policies (SCPs) can be applied to either an organizational units (OU) or an individual member account.

### Compliance

AWS Artifact is a service that provides on-demand access to AWS security and compliance reports and select online agreements.

The Customer Compliance Center contains resources to help us learn more about AWS compliance.

### Denial-of-Service Attacks

A denial-of-service (DoS) attack is a deliberate attempt to make a website or application unavailable to users.

In a distributed denial-of-service (DDoS) attack, multiple sources are used to start an attack that aims to make a website or application unavailable.

### Additional Security Services

AWS Key Management Service (AWS KMS) enables us to perform encryption operations through the use of cryptographic keys.

A cryptographic key is a random string of digits used for encrypting and decrypting data.

AWS WAF is a web application firewall that lets us monitor network requests that come into our web applications.

It does this by using access control lists (ACLs) to protect our AWS resources.

Amazon Inspector helps to improve the security and compliance of applications by running automated security assessments.

Amazon GuardDuty is a service that identified threats by continously monitoring network activity and account behavior within our AWS environment.

## Section 7 -- Monitoring & Analytics

### Amazon CloudWatch

Amazon CloudWatch is a web service that enables us to monitor and manage various metrics and configure alarm actions based on data from those metrics.

### AWS CloudTrail

AWS CloudTrail records API calls for our account.

Using CloudTrail we can view a complete history of user activity and API calls for our applications and resources.

With CloudTrail we can also enable CloudTrail Insights which is an optional feature that allows CloudTrail to automatically detect unusual API activities in our AWS account.

### AWS Trusted Advisor

AWS Trusted Advisor is a web service that inspects our AWS environment and provides real-time recommendations in accordance with AWS best practices in five categories: cost optimization, performance, security, fault tolerance, and service limits.

## Section 8 -- Pricing & Support

### AWS Pricing Calculator

The AWS Pricing Calculator lets us explore AWS services and create a cost estimate for our use cases on AWS.

### AWS Billing & Cost Management Sashboard

We can use the AWS Billing & Cost Management Dashboard to pay our AWS bill, monitor our usage, and analyze/control our costs.

### AWS Budgets

Using AWS Budgets we can create budgets to plan our service usage, service costs, and instance reservations.

The information in AWS Budgets updates three times per day.

### AWS Cost Explorer

AWS Cost Explorer is a tool that enables us to visualize, understand, and manage our AWS costs and usage over time.

### AWS Support Plans

AWS support plans offer pay-by-the-month pricing and requires no long-term contracts.

The Enterprise Support plan includes access to a Technical Account Manager (TAM).

The TAM provides guidance, architectural reviews, and ongoing communication with our company as we plan, deploy, and optimize our applications.

## Section 9 -- Migration & Innovation

### AWS Cloud Adoption Framework (AWS CAF)

The AWS Cloud Adoption Framework (AWS CAF) leverages AWS experience and best practices to help us digitally transform and accelerate our business outcomes through innovative use of AWS.

The AWS CAF organizes guidance into six areas of focus called Perspectives.

Those six Perspectives are: Business, People, Governance, Platform, Security, and Operations.

### Migration Strategies

The 6 most common strategies for migrating applications to the cloud are:

- **Rehosting** -- Moving applications without making changes
- **Replatforming** -- Making a few cloud optimizations to realize a tangible benefit
- **Refactoring** -- Reimagining how an application is architected and developed by using cloud-native features
- **Repurchasing** -- Moving from a traditional license to a software-as-a-service model
- **Retaining** -- Keeping applications that are critical for the business in the source environment
- **Retiring** -- Removing applications that are no longer needed

### AWS Snow Family

The AWS Snow Family is a collection of physical devices that can be used to physically transport up to exabytes of data.

AWS Snowcone features 2 CPUs, 4 GB of memory, and 8 TB of usable storage.

Snowball Edge Storage Optimized devices are well suited for large-scale data migrations and recurring transfer workflows.

Snowball Edge Compute Optimized devices provide powerful computing resources for use cases such as machine learning, full motion video analysis, analytics, and local computing stacks.

## Section 10 -- The Cloud Journey

### AWS Well-Architected Framework

The AWS Well-Architected Framework helps us to understand how to design and operate reliable, secure, efficient, and cost-effective systems in the AWS Cloud.

The five pillars of the Well-Architected Framework are:

- Operational excellence
- Security
- Reliability
- Performance efficiency
- Cost optimization
