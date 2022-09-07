# Account Management & Billing

## AWS Organizations

_AWS Organizations_ is a global service that allows us to manage multiple AWS accounts.

The main benefit of using AWS Organizations is that it offers consolidated billing and we can enjoy price benefits from aggregated usage (volume discounts).

We can use _service control policies_ (SCP) to whitelist or blacklist IAM actions.

These SCPs can then be applied at an _organization unit_ (OU) or account level.

## AWS Control Tower

_AWS Control Tower_ runs on top of AWS Organizations and is an easy way to set up and govern a secure and compliant multi-account AWS environment.

## Cloud Pricing Models

AWS has 4 pricing models:

- Pay as you go
- Save when you reserve
- Pay less by using more
- Pay less as AWS grows

## AWS Compute Optimizer

_AWS Compute Optimizer_ uses machine learning to analyze our resources' configuration and their utilization CloudWatch metrics.

Compute Optimizer is then able to reduce costs and improve performance by recommending optimal AWS resources for our workloads.

## AWS Trusted Advisor

_AWS Trusted Advisor_ analyzes our AWS accounts and provides recommendations on 5 categories

1. Cost optimization
1. Performance
1. Security
1. Fault tolerance
1. Service limits
