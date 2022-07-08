# Computing Services

## Elastic Compute Cloud (EC2)

_Elastic Compute Cloud_ (EC2) allows us to launch _Virtual Machines_ (VMs).

_Server Virtualization_ allows us to easily create, copy, resize, or migrate servers.

An _Amazon Machine Image_ (AMI) is a predefined configuration for a Virtual Machine.

EC2 is a highly configurable server where we can choose from different AMIs that affect options such as:

- Amount of CPUs
- Amount of RAM
- Amount of Network Bandwidth
- Operating System (OS)

EC2 is considered the backbone of AWS because the majority of AWS services are using EC2 as their underlying servers.

## Other Popular Computing Services

**Amazon LightSail** -- A managed virtual server service that is basically a lighter version of EC2 for those with less technical knowledge.

**Elastic Container Service (ECS)** -- A container orchestration service that supports Docker containers.

**Elastic Container Registry (ECR)** -- A repository for container images.

**ECS Fargate** -- A serverless orchestration container service.

**Elastic Kubernetes Service (EKS)** -- A fully managed Kubernetes service.

**AWS Lambda** -- A serverless functions service where we are charged based on the runtime of the serverless functions rounded to the nearest 100ms.

## Higher Performance Computing Services

_High Performance Computing_ (HPC) is a cluster of hundreds of thousands of servers with fast connections between each of them with the purpose of boosting computing capacity.

HPC is used when you need a supercomputer to perform computation problems that are too large to run on standard computers, or that would take too long.

_AWS ParallelCluster_ is an AWS-supported open source cluster management tool that makes it easy to deploy and manage HPC clusters on AWS.
