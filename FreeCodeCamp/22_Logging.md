# Logging Services

## AWS CloudTrail

Logs all API calls between AWS services.

This can help us to detect developer misconfigurations and malicious actors.

Some of the logged information includes the

- **Where** -- Source IP Address
- **When** -- EventTime
- **Who** -- User, UserAgent
- **What** -- Region, Resource, Action

## CloudWatch

A collection of multiple services such as:

- **Logs** -- A centralized place to store cloud service log data or application logs

- **Metrics** -- A time-ordered set of data points.

- **Events/EventBridge** -- Trigger an event based on a condition

- **Alarms** -- Trigger notifications based on metrics

- **Dashboard** -- Create visualizations based on metrics

## AWS X-Ray

A distributed tracing system that can be used to pinpoint issues with our microservices.

It can help us to see how data moves from one app to another, how long it took to move, and if it failed to move forward.
