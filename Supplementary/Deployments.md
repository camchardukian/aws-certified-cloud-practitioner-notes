# Deployments & Infrastructure

## CloudFormation

_CloudFormation_ is a declarative way of outlining our AWS Infrastructure.

One of the largets benefits of using CloudFormation is that resources are no longer manually created, which is excellent for control.

Using CloudFormation also results in any changes to the infrastructure having to go through a code review.

## AWS Cloud Development Kit (CDK)

The _CDK_ allows us to define our cloud infrastructure using a familiar language such as JavaScript, or Python which can then be compiled into a CloudFormation template.

## Elastic Beanstalk

_Elastic Beanstalk_ is a managed _Platform as a Service_ (PaaS) that offers a developer centric view of deploying an application on AWS.

## CodeDeploy

_CodeDeploy_ is a hybrid service that allows us to deploy our application automatically.

CodeDeploy works with both EC2 Instances, and On-Premise Servers but said servers/instances must be provisioned and configured ahead of time with the CodeDeploy Agent.

## CodeCommit

_CodeCommit_ is basically the AWS competing product for GitHub.

## CodeBuild

_CodeBuild_ compiles source code, runs tests, and produces packages that are ready to be deployed.

CodeBuild is fully managed, serverless, and offers pay-as-you-go-pricing where you only pay for the build time.

## CodePipeline

_CodePipeline_ orchestrates the different steps to have our code automatically pushed to production and can serve as the basis for CI/CD (continuous integration & continuous delivery).

## CodeArtifact

_CodeArtifact_ is an artifact management service.

_Artifact management_ refers to storing and retrieving the different dependencies our app needs in order to be built.

## CodeStar

_CodeStar_ offers a unified UI and a quick way for us to correctly set-up our CI/CD in AWS.

## Cloud9

_Cloud9_ is a cloud IDE (integrated development environment) similar to Visual Studio Code, but because it is in the cloud it doesn't need to be downloaded prior to being used.

Cloud9 also allows for pair programming in real-time.

## Systems Manager (SSM)

_Systems Manager_ is a hybrid AWS service that allow us to manage our EC2 and On-Premise systems at scale.

Systems Manager allows us to run commands across an entire fleet of servers and automate patching for enhanced compliance.
