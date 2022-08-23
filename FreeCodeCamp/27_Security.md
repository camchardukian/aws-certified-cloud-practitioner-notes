# Security

## The 7 Layers of Security

1. **Data** -- Access to business and customer data, and encryption to protect data.
1. **Application** -- Applications are secure and free of security vulnerabilities.
1. **Compute** -- Access to virtual machines (ports, on-premise, cloud)
1. **Network** -- Limit communication between resources using segmentation and access controls
1. **Perimeter** -- Distributed denial of service (DDoS) protection to filter large-scale attacks before they can cause a denial of service for users.
1. **Identity and access** -- Controlling access to infrastructure and change control
1. **Physical** -- Limiting access of a datacenter to only authorized personnel.

## CIA Model

The _Confidentiality, Integrity, and Availability (CIA)_ triad is a model describing the foundation to security principles and their trade-off relationship.

## Vulnerabilities

A _vulnerability_ can be defined as a hole or weakness in an application such as a design flaw or implementation bug that allows an attacker to cause harm to the stakeholders of an application.

## Encryption

_Cryptography_ is the practice and study of techniques for secure communication in the presence of third parties called adversaries.

_Encryption_ is the process of encoding (scrabbling) information using a key and a cypher to store sensitive data in an unintelligible format as a means of protection.

## Cyphers

A _cypher_ is an algorithm that performs encryption or decryption.

_Ciphertext_ is the result of encryption performed on plaintext via an algorithm.

## Cryptographic Keys

A _cryptographic key_ is a variable used in conjunction with an encryption algorithm in order to encrypt or decrypt data.

In _symmetric encryption_ methods the same key is used for encoding and decoding whereas in _asymmetric encryption_ one key is used for encoding while another is used for decoding.

## Digital Signatures and Signing

A _digital signature_ is a mathematical scheme for verifying the authenticity of digital messages or documents.

Digital signatures rely on three algorithms:

- **Key generation** -- generates a public and private key
- **Signing** -- The process of generating a digital signature with a private key and inputted message.
- **Signing verification** -- Verifies the authenticity of a message with a public key.

We can use digital signatures to do _code signing_ which basically means to ensure via a digital signature that computer code has not been tampered with.

## In-Transit vs At-Rest Encryption

_Encryption In-Transit_ refers to data that is secure when moving between locations.

_Encryption At-Rest_ refers to data that is secure when residing on storage or within a database.

## Penetration Testing

_Penetration testing_ or _pen testing_ refers to an authorized simulated cyberattack on a computer system performed to evaluate the security of the system.

## AWS Artifact

_AWS Artifact_ is a self-serve portal for on-demand access to AWS compliance reports.

## AWS Inspector

_Hardening_ is the act of eliminating as many security risks as possible.

## Distributed Denial of Service (DDoS)

_Distributed Denial of Service (DDoS)_ Attack is a malicious attempt to disrupt normal traffic by flooding a website with large amounts of fake traffic.

## AWS Shield

_AWS Shield_ is a managed DDoS protection service that safeguards applications running on AWS.

AWS Shield Standard is free and protects against most common DDoS attacks while AWS Shield Advanced costs $3,000+/year and provides additional protection against larger and more sophisticated attacks.

## Amazon Guard Duty

_Guard Duty_ is a threat detection service that continuously monitors for malicious, suspicious activity and unauthorized behavior.

## Amazon Macie

_Macie_ is a fully managed service that continously monitors S3 data access activity for anomalies, and generates detailed alerts when it detects risk of unauthorized access of inadvertent data leaks.

## AWS WAF

_AWS Web Application Firewall (WAF)_ protects your web application from common web exploits.

## Hardware Security Module (HSM)

A _Hardware Security Module (HSM)_ is a piece of hardware designed to store encryption keys.

HSMs hold keys in memory and never write them to a disk.

The _Federal Information Processing Standard (FIPS)_ is the US and Canadian governments' standard that specifies the security requirements for cryptographic modules that protect sensitive information.

## AWS Key Management Service

_AWS Key Management Service (KMS)_ is a managed service that makes it easy for you to create and control the encryption keys used to encrypt your data.

## CloudHSM

_CloudHSM_ is a single-tenant HSM as a service that automates hardware provisioning, software patching, high availability and backups.

AWS CloudHSM enables us to generate and use our encryption keys on FIPS 140-2 Level 3 validated hardware.
