# VPC & Networking

## VPC

A _Virtual Private Cloud_ or _VPC_ is a private network to deploy your resources.

_Subnets_ allow us to partition our network inside our VPC.

A _public subnet_ is a subnet that is accessible from the internet.

A _private subnet_ is a subnet that is not accessible from the internet.

_Internet Gateways_ help our VPC instances connect with the internet.

Our public subnets will have a route to the internet gateway.

_NAT Gateways_ (AWS-managed) and _NAT Instances_ (self-managed) allow the instances in our private subnets to access the internet while remaining private.

## Security Groups & Network ACL

A _NACL_ or _Network ACL_ is a firewall which controls traffic to and from the subnet.

NACLs can have ALLOW and DENY rules and are attached at the subnet level.

_Security Groups_ are a firewall that controls traffic to and from an ENI/EC2 instance.

Security Groups can only have ALLOW rules.

_VPC Endpoints_ allow us to connect to AWS services using a private network instead of the public www network.

## AWS PrivateLink

_PrivateLink_ is the most secure and scalable way to expose a service to 1000s of VPCs.

It provides private connectivity between VPCs, AWS services, and our on-premise networks without exposing our traffic to the public internet.

## Site to Site VPN & Direct Connect

**Site to Site VPN** -- Connect an on-premises VPN to AWS and goes over the public internet.

**Direct Connect (DX)** -- Establishes a physical connection between on-premises and AWS. Goes over a private network and is more secure/faster, but takes at least a month to establish.
