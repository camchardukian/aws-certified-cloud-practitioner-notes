# Cloud Monitoring

## CloudWatch Overview

_CloudWatch_ provides metrics for every service in AWS.

A _metric_ is a variable to monitor such as CPU utilization.

If a metric you'd like to monitor does not yet exist within CloudWatch, it's also possible to create your own metrics.

Alarms can also be set to automate notifications, perform EC2 actions, notify to SNS, etc., based on metric thresholds being met.

## CloudWatch Logs

_CloudWatch Logs_ can collect log info from Elastic Beanstalk, ECS, AWS Lambda, CloudTrail, CloudWatch log agents on EC2 machines or on-premise servers, or Route53.

## Amazon EventBridge

_Amazon EventBridge_ (formerly CloudWatch Events), is a serverless event bus that makes it easier to build event-driven applications at scale using events generated from our applications, integrated SaaS applications, and AWS services.

## CloudTrail

_CloudTrail_ monitors and records account activity across our AWS infrastructure.

It is enabled by default and can be useful for governance, compliance, and auditing for our AWS account.

There are three types of CloudTrail events:

1. **Management Events** -- Operations that are performed on resources in our AWS account (logged by default in CloudTrail)
1. **Data Events** -- Operations such as Amazon S3 object-level activity, and AWS Lambda function execution activity (not logged by default in CloudTrail due to data events typically being high frequency, thus additional fees may be applicable)

1. **CloudTrail Insights Events** -- CloudTrail will monitor out account and attempt to detect unusual activity such as inaccurate resource provisioning, bursts of AWS IAM actions, gaps in periodic maintenance activity, etc. (not enabled by default, and requires payment to enable)

## X-Ray

_AWS X-Ray_ helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture.

## CodeGuru

_CodeGuru_ is an ML-powered service for automated code reviews and application performance recommendations.

## Service & Personal Health Dashboard

The _Service Health Dashboard_ displays the general status of AWS services.

The _Personal Health Dashboard_ gives a personalized view into the performance and availability of the AWS services underlying our AWS resources.
