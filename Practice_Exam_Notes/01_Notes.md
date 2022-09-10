# Practice Exam 01 Notes

## AWS Shared Responsibility Model

Configuration management is a shared responsibility between the customer and AWS.

AWS maintains the configuration of its infrastructure devices, but the customer is responsible for configuring their own guest operating systems, databases, and applications.

## Amazon RDS

Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud.

The primary benefit of deploying an RSD database in a Read Replica configuration is that it improves database scalability.

To improve availability, we should use Amazon RDS Multi-AZ deployments.

## AWS Pricing Calculator

AWS Pricing Calculator lets us explore AWS services and create an estimate for the cost of our use cases on AWS.

## AWS Cost Explorer

AWS Cost Explorer is used to explore and analyze our historical spend and usage on AWS.

## VPC Peering

A VPC peering connection is a networking connection between two VPCs that enables us to route traffic between them privately.

## AWS Direct Connect

AWS Direct Connect creates a dedicated private connection from a remote network to our VPC.

## AWS Config

AWS Config is a service that enables us to assess, audit, and evaluate the configuration of our AWS resources.

## Amazon Inspector

Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS.

## Amazon Elastic File System

Amazon Elastic File System (EFS) provides scalable file storage for use with both AWS cloud services and on-premise resources.

Amazon EFS is built to be able to grow and shrink automatically as files are added and removed.

## AWS OpsWorks

AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet.

## Amazon Elastic Container Service (Amazon ECS)

Amazon ECS is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers on a cluster.

Because this service is not fully managed, we are able to manage the underlying servers ourselves.

## CloudWatch, CloudTrail, AWS Config

CloudWatch -- Generally used for resource monitoring, events, and alerts.

CloudTrail -- Account-specific activity and auditing.

AWS Config -- Resrouce-specific change history, auditing, and compliance.

## Amazon DynamoDB

Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale.

DynamoDB global tables replicate data automatically across our choice of AWS regions and automatically scale capacity to accomodate our workloads.

## AWS Edge Locations vs Local Zones

AWS Edge Locations seem to be used mostly with CloudFront for assisting in caching content and CDNs, whereas Local Zones are extensions of AWS Regions.

Using Local Zones we can place resources such as compute and storage in multiple locations closer to our scattered users, thus providing them with lower latency.

## APN Consulting Parters

APN (Amazon Partner Network) Consulting Partners are professional service firms that help customers of all types and sizes design, architect, build, migrate, and manage their workloads and applications on AWS.

## AWS CodeDeploy

AWS CodeDeploy is a service that automates code deployments to any instance, including Amazon EC2 instances and instances running on-premises.

AWS CodeDeploy can be used to automate deployments, eliminating the need for error-prone manual operations, and the service scales with out infrastructure so that we can easily deploy to one instance or thousands.

## Virtual MFA Device

A software app that runs on a phone or other device and emulates a physical device.

## Amazon Elastic Block Store (EBS)

Amazon EBS is a high-performance block storage service.

## U2F Security Key

This is a device that you can plug into a USB port on your computer for multi-factor authentication.

## AWS X-Ray

A service that can be used to analyze and debug serverless and distributed applications such as those built using a microservices architecture.

## Auto Scaling

Auto Scaling helps us ensure that we always have the correct number of EC2 instances available to handle the load for our application.
