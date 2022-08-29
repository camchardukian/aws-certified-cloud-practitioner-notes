# EC2

## General Info

_EC2_ or "Elastic Compute Cloud" instances can be bootstrapped using an EC2 User data script.

The term bootstrapping in this context refers to launching commands when a machine starts and can be used to automate boot tasks such as:

- Installing updates
- Installing software
- Downloading common files from the internet
- Almost anything else you can think of

If you stop an instance and restart it, it's likely the instance's public IP address will change.

The private IP address on the other hand shouldn't change.

## EC2 Instance Types

**General Purpose** -- Great for a diversity of workloads such as web servers or code repositories.

**Compute Optimized** -- Great for compute-intensive tasks such as media transcoding, machine learning, or dedicated gaming servers.

**Memory Optimized** -- Fast performance for workloads that process large data sets in memory such as relational/non-relational databases, or applications performing real-time processing of big unstructured data.

**Storage Optimized** -- Great for storage-intensive tasks that require high, sequential read and write access to large data sets on local storage such as relational/NoSQL databases, data warehousing applications, and distributed file systems.

## Security Groups

Security groups control how traffic is allowed into or out of our EC2 instances.

Security groups can be attached to multiple instances and multiple security groups can attach to a single instance.

## EC2 Instance Purchasing Options

**On-Demand** -- short workload, predictable pricing, pay by the second/hour depending on OS

**Reserved** -- Long workloads

**Savings Plans** -- Commitment to an amount of usage, long workloads

**Spot Instances** -- short workloads, cheap, can sometimes be less reliable

**Dedicated Hosts** -- Book an entire physical server, control instance placement

**Dedicated Instances** -- No other customers will share your hardware

**Capacity Reservations** -- Reserve capacity in a specific AZ for any duration.

## EC2 Instance Storage

### EBS

An EBS (Elastic Block Store) Volume is a network drive we can attach to our instances while they run.

They can be quickly attached from one EC2 instance to another but are locked to a specific availability zone.

EBS Volumes can also be left unattached or we can have multiple EBS Volumes attached to a single EC2 instance.

We can make a "copy" of an EBS volume's data at a specific point in time using the _EBS Snapshots_ feature.

### AMI

AMI stands for _Amazon Machine Image_. AMIs are a customization of an EC2 instance.

### EC2 Instance Store

_EC2 Instance Stores_ are high performance hardware disks that are great for buffer/cache/temporary content, but they lose their storage if they are stopped.

### EFS

EFS (Elastic File System) is a managed NFS (network file system) that can be mounted to 100s of EC2 instances.

### Amazon FSx

A fully managed service for launching 3rd party high performance file systems on AWS.
