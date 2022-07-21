# EC2 Pricing Models

The five different ways to pay for EC2 (Virtual Machines) are:

1. On-Demand
1. Spot
1. Reserved
1. Dedicated
1. AWS Savings Plan (which can also be used for other services)

## On-Demand

_On-Demand_ is a _pay-as-you-go_ (PAYG) model that is set as the default when launching an EC2 instance.

On-Demand is great for new app development or for applications with short-term, spikey, or unpredictable workloads.

## Reserved Instances (RI)

Designed for applications that have steady-state, predicatable usage, or that require reserved capacity.

Savings can be had based on term lengths, class offering, RI attributes, and payment options.

## RI Attributes

The four RI attributes are:

1. Instance type
1. Region
1. Tenancy
1. Platform

## RI Limits

Each month you can purchase:

- 20 Regional Reserved Instances per Region
- 20 Zonal Reserved Instances per AZ

## Capacity Reservations

_Capacity Reservation_ is a service of EC2 that allows you to request a reserve of EC2 instance type for a specific Region and AZ.

## RI Marketplace

_EC2 Reserved Instance Marketplace_ allows you to sell your unused Standard RI (though there are some terms and conditions that must be met prior to selling).

## Spot Instances

AWS offers spot instances so that it is able to maximize the uility of its idle servers.

Spot instances provide a discount of up to 90% compared to On-Demand pricing.

_AWS Batch_ is an easy and convenient way to use Spot Pricing.

## Dedicated Instances

Dedicated Instances are designed to meet regulatory requirements.

## AWS Savings Plan

_AWS Savings Plans_ offer similar discounts to _Reserved Instances_ (RI), but offer a simpler purchasing process.
