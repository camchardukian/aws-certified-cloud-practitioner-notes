# Compute Services

## ECS

_ECS_ or "Elastic Container Service" is used to launch Docker containers on AWS.

With ECS we must provision and maintain the infrastructure (the EC2 instances).

## Fargate

_Fargate_ is also used to launch Docker containers on AWS but with Fargate we do not need to provision the infrastructure.

## ECR

_ECR_ or "Elastic Container Registry" is a private Docker registry on AWS where we can store our Docker images so that they can be run by ECS or Fargate.

## Serverless

_Serverless_ is a new paradigm in which the developers no longer have to manage the servers.

Serverless doesn't mean that there are no servers, it just means that it isn't our responsibility to provision/manage them.

## AWS Lambda

_Amazon Lambda_ is an event-driven reactive type of service where functions will only get invoked when needed.

Lambda pricing is based on pay per request and compute time.

It is usually very cheap to run AWS Lambda which is why it's very popular.

## API Gateway

_Amazon API Gateway_ is a fully managed service for developers to easily create, publish, maintain, monitor, and secure APIs.

API Gateway supports RESTful APIs and WebSocket APIs while being serverless and scalable.

## AWS Batch

_AWS Batch_ enables us to easily and efficiently run hundreds of thouands of batch computing jobs on AWS.

## Amazon Lightsail

_Amazon Lightsail_ can be used for virtual servers, storage, databases, and networking.

It is a simpler alternative to using EC2, RDS, ELB, etc., and is great for people with little cloud experience.
