# Databases

With relational databases we can use the SQL language to perform queries/lookups.

Non relational/NoSQL databases have flexible schemas are are easier to horizontally scale.

## RDS

_RDS_ stands for _Relational Database Service_.

RDS allows us to create databases in the cloud that are managed by AWS.

## ElastiCache

_ElastiCache_ is used to get managed Redis or Memcached.

ElastiCache is useful for providing high performance and low latency.

## DynamoDB

_DynamoDB_ is a fully managed highly available NoSQL database.

DynamoDB is a key/value database.

_DynamoDB Accelerator_ or "DAX", is a fully managed in-memory cache for DynamoDB.

DAX is only used for and integrated with DynamoDB while ElastiCache can be used for other databases.

## Redshift

_Redshift_ is based on PostgreSQL and is good for online analytical processing (OLAP).

It only loads data once every hour instead of every second, but it provides 10x better performance than other data warehouses.

## EMR

_EMR_ stands for "Elastic MapReduce" and is used for creating Hadoop clusters to analyze and process vast amounts of data.

## Athena

_Athena_ analyzes data in S3 using serverless SQL at a cost of around $5.00 per TB of data scanned.

## QuickSight

_QuickSight_ is a serverless machine learning-powered business intelligence service to create interactive dashboards.

## DocumentDB

DocumentDB is Amazon's only managed MongoDB compatible service.

## Neptune

_Amazon Neptune_ is a fully managed graph database.

It is ideal for building and running applications with highly connected datasets.

Some ideal use cases for Neptune would be knowledge graphs (like Wikipedia), recommendation engines, and social networks.

## QLDB

_Amazon QLDB_ or "Quantum Ledger Database" is a fully managed, serverless, highly available database with _ledgers_.

A ledger is a book recording financial transactions that allows us to review the history of all the changes made to our application data over time.

It is an immutable database system with the option of being cryptographically verifiable.

## Amazon Managed Blockchain

_Amazon Managed Blockchain_ is a managed service that allows us to join public blockchain networks, or create our own scalable private networks.

It is compatible with Hyperledger Fabric and Ethereum.

## AWS Glue

_Glue_ is a managed extract, transform, and load (ETL) service that is useful for preparing and transforming data for analytics.
