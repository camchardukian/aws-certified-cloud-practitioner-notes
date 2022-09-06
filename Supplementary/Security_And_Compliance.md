# Security & Compliance

AWS is responsible for the "Security of the Cloud" while the customer is responsible for the "Security in the Cloud".

## DDos Protection

A distributed _denial-of-service_ (DDoS) attack is a malicious attempt to disrupt the normal traffic of a targeted server, service, or network by overwhelming the target or its surrounding infrastructure with a flood of internet traffic.

We can protect against DDoS attacks on AWS by using:

- AWS Shield Standard: protects against DDoS attacks for our website and applications at no additional costs

- AWS Shield Advanced: 24/7 premium DDoS protection

- AWS WAS: Filter specific requests based on rules

## Penetration Testing

A _penetration test_ or _pen test_ is basically a form of ethical hacking where we simulate a cyberattack on a computer system to evaluate its security.

## Encryption

Ideally we want our data to be encrypted both at rest and in transit.

_AWS KMS_ manages encryption keys for us.

With CloudHSM, AWS provisions encryption hardware for us and we are then responsible for managing our encryption keys.

## AWS Certificate Manager (ACM)

_ACM_ is used to easily provision, manage, and deploy SSL/TLS certificates.

ACM can help to remove the time-consuming manual process of purchasing, uploading, and renewing SSL/TLS certificates.

## Secrets Manager

_AWS Secrets Manager_ is a newer service used for storing secrets.

It can also force the rotation of secrets every X days.

Secrets Manager is mostly used for RDS integration.

## GuardDuty

_Amazon GuardDuty_ uses machine learning algorithms to detect anomalies or possible threats to our AWS account.

## Amazon Inspector

_Amazon Inspector_ is an automated vulnerability management service that continually scans AWS workloads for software vulnerabilities and unintended network exposure.

## AWS Config

_AWS Config_ is helpful for auditing and recording compliance of our AWS resources over time.

## Macie

_Macie_ is a fully managed data security and data privacy service that uses machine learning and pattern matching to discover and protect our sensitive data in AWS.

## Security Hub

_AWS Security Hub_ is a security tool to manage security across several AWS accounts and automate security checks.

## Amazon Detective

_Amazon Detective_ analyzes, investigates, and quickly identifies the root cause of security issues and suspicious activities.
