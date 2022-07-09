# Storage

## Types of Storage Services

Three types of storage are:

1. Block -- via _Elastic Block Store_ (EBS)
1. File -- via _AWS Elastic File Storage_ (EFS)
1. Object -- via _Amazon Simple Storage Service_ (S3)

## Introduction to S3

_Object storage_ or _object-based storage_ is a type of data storage architecture that manages data as objects as opposed to file systems or block storage.

S3 provides us with unlimited storage.

S3 Objects contain data and may consist of a key, value, version ID, and metadata.

S3 Buckets hold objects and may contain folders which also hold objects.

Similar to domain names, S3 bucket names must be unique because they share a universal namespace.

## S3 Storage Classes

AWS offers a range of S3 storage classes that trade **retrieval time**, **accessibility**, and **durability** for cheaper storage.

## AWS Snow Family

AWS Snow Family are storage and compute devices used to physically move data in or out of the cloud when moving data over the internet or a private connection are too slow, difficult or costly.
