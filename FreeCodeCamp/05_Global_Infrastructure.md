# Global Infrastructure

## Regions

_Regions_ are geographically distinct locations made up of one or more availability zones.

Launched in 2006, US-East 1 was AWS's first region.

Each region generally has three _availability zones_.

Not all AWS services are available in every region and costs can also vary from region to region.

New services typically become first available in US-East 1.

Four factors to consider when choosing a region are: cost, distance/latency for users, service availability, regulatory compliance.

## Global Services

Some AWS services operate across multiple regions and thus their region will be fixed as global.

## Availability Zones (AZ)

An _Availability Zone_ is a physical location made up of one or more _datacenters_.

A datacenter is a secured building that houses hundreds or thousands of computers.

## Fault Tolerance

A _fault domain_ is a section of a network that is vulnerable to damage if a critical device or system fails.

The purpose of a fault domain is that if a failure occurs, the failure will not cascase outside of that fault domain, thus limiting damage.

A _fault level_ is a collection of fault domains.

## AWS Global Network

The AWS Global Network is commonly referred to as "The Backbone of AWS" and its purpose is to help things move quickly between data centers.

## Point of Presence

For AWS a _Point of Presence_ (PoP) is a data center owned by AWS or a trusted partner that is utilized by AWS services related to content delivery or expediated upload.

Two examples of PoPs are _Edge Locations_ and _Regional Edge Locations_.

### Edge Locations

Datacenters that hold cached copies of the most popular files.

### Regional Edge Locations

Datacenters that hold larger caches of less-popular files.

## AWS Services Using PoPs

Three AWS services that use PoPs are:

1. Amazon CloudFront
1. Amazon S3 Transfer Acceleration
1. AWS Global Accelerator

## AWS Direct Connect

AWS _Direct Connect_ is a private/dedicated connection between your datacenter, office, co-location and AWS.

Direct Connect has two connection options:

1. Lower Bandwidth (50MB-500MB per second)
1. Higher Bandwidth (1GB-10GB per second)

## Local Zones

_Local Zones_ are datacenters located very close to densely populated areas that provide single-digit millisecond low latency performance for the area.

The purpose of Local Zones is to support highly-demanding applications that are sensitive to latency.

## Data Residency

_Data Residency_ refers to the physical or geographic location where an organization or cloud resources reside.

_Compliance Boundaries_ are regulatory/legal requirements by a government or organization that describe where data and cloud resources are allowed to reside.

_Data Sovereignty_ is the jurisdictional control or legal authority that can be asserted over data because of its physical location within jurisdictional boundaries.

## GovCloud

AWS offers isolated regions called _GovCloud_ that allows customers to host sensitive **Controlled Unclassified Information** and other types of regulated workloads.

GovCloud regions are only operated by employees who are U.S. citizens on U.S. soil.

## AWS in China

In order to operate in an AWS China Region you need a Chinese Business License.

The benefit of running in mainland China (instead of Singapore) is that you wouldn't need to traverse "The Great Firewall".

## Sustainability

Amazon has sustainability goals related to renewable energy, cloud efficiency, and water stewardship.

## AWS Ground Station

_AWS Ground Station_ is a fully managed service that lets you control satellite communications, process data, and scale your operations without having to worry about building or managing your own ground station infrastructure.

## AWS Outposts

AWS Outpots is a rack of servers running AWS infratructure at your physical location.
