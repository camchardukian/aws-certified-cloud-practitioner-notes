# Databases

## Database Types

_Relational databases_ have structured data that represent tabular data, whereas _non-relational_ databases have data that may not resemble tabular data.

## Data Warehouse

A _data warehouse_ is a relational datastore designed for analytic workloads.

Data warehouses are optimized around columns since they need to quickly aggregate column data.

## Document Store

A _document store_ is a NoSQL database that stores documents as its primary data structure.

A document could be XML but more commonly is JSON or JSON-like.

## NoSQL Database Services

**DynamoDB** -- A serverless NoSQL key/value and document database and AWS's flagship database service.

**DocumentDB** -- A NoSQL document database that is "MongoDB compatible". Because there were open-source licensing issues around using open-source MongoDB, AWS simply built their own MongoDB database.

**Amazon Keyspaces** -- A fully managed Apache Cassandra database that is similar to DynamoDB but with some additional functionality.

## Relational Database Services

_Relational Database Service_ (RDS) is a relational database service that supports multiple SQL engines such as:

- MySQL
- MariaDB
- Postgres (PSQL)
- Oracle
- Microsoft SQL Server
- Aurora

_Aurora_ is a fully managed database of either MySQL or PSQL.

## Other Database Services

**Redshift** -- A petabyte-size data-warehouse that can be used for _online analytical processing_ (OLAP).

**Elasticache** -- A managed caching service for Redis and Memcached.

**Neptune** -- A managed graph database.

**Amazon Timestreams** -- A fully managed time series database.

**Amazon Quantum Ledger Database** -- A fully managed ledger database that provides transparent, immutable and cryptographically variable transaction logs.

**Database Migration Service** (DMS) -- A database migration service.
