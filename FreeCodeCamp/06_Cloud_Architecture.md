# Cloud Architecture

## Cloud Architecture Terms

A _solutions architect_ is a role in an organization focused on architecting a technical solution using multiple systems via research, documentation, and experimentation.

A _cloud architect_ is a role focused solely on architecting technical solutions using cloud services.

## High Availability

Our application is much more likely to have high availability if we use _load balancers_ and ensure there is no single point of failure (such as by utilizing multiple servers).

## High Scalability

_Vertical scaling_ refers to upgrading to a larger server while _horizontal scaling_ refers to adding more servers.

## High Elasticity

We can scale out (by adding more servers), or scale in (by removing underutilized servers).

_Auto Scaling Groups_ (ASG) is an AWS feature that will automatically add or remove servers based on scaling rules we define.

## Fault Tolerance

A _fail-over_ is when you have a plan to shift traffic to a secondary system in case the primary system fails.

Using _RSD Multi-AZ_ we can run a duplicate standby database in another Availability Zone just in case our primary database fails.

## Durability

The ability to recover from a disaster and prevent the loss of data is known as _disaster recovery_ (DR).

One AWS service we can use to contribute to our disaster recovery efforts is _CloudEndure Disaster Recovery_.

## Business Continuity Plan

A _business continuity plan_ (BCP) is a document that outlines how a business will continue operating during an unplanned distruption in services.

_Recovery Point Objective_ (RPO) refers to the maximum amount of acceptable data loss expressed in units of time after an unplanned data-loss incident.

_Recovery Time Objective_ (RTO) refers to the maximum amount of downtime the business can tolerate without incurring a significant financial loss.
