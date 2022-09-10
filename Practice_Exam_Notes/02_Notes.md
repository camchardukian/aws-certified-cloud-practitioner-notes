# Practice Exam 02 Notes

## AWS Shield Advanced

Provides expanded DDoS attack protection for web applications running on the following resources: Amazon EC2, ELB, CloudFront, Route 53, and AWS Global Accelerator.

## VPC Endpoints

A VPC endpoint enables us to privately connect our VPC to supported AWS services and VPC endpoint services powered by AWS PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connectoin.

## Amazon Inspector & Amazon GuardDuty

Amazon GuardDuty is a threat detection service that operates at an AWS account level while Amazon Inspector is an automated security assessment service that operates on an instance level for EC2.

## Instance Stores

An instance store provides temporary block-level storage for our instance.

This storage is located on disks that are physically attached to the host computer.

This is a good option when we need storage with very low latency, but we don't need the data to persist when the instance terminates.

## AWS Regions & Availability Zones

Each AWS Region consists of two or more Availability Zones.

Each Availability Zone consists of one or more discrete data centers.

## Security Groups

Security groups act as a virtual firewall for our instance to control inbound and outbound traffic.

With security groups we can specify allow rules, but not deny rules.
