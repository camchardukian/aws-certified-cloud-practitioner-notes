# Containers

## VMs vs Containers

VMs do not make the best use of space, and apps are not isolated which can cause config conflicts, security problems, or resource hogging.

Containers on the other hand allow us to run multiple apps which are virtually isolated from each other.

We're also able to configure OS dependencies inside of each individual container.

## Microservices

Using a _Microservices Architecture_ approach we have multiple apps which are each responsible for one thing.

By integrating with different cloud services we actually end up using a microservices approach whether we realize it or not.

## Kubernetes

Kubernetes is an open-source container orchestration system for automating deployment, scaling and management of containers.

Kubernetes is ideal for microservice architectures where a company has tens to hundreds of services they need to manage.

## Docker

Docker is a set of Platform as a Service (PaaS) products that use OS-level virtualization to deliver software in packages called containers.

## Podman

Podman along with Buildah and Skopeo can be used a replacement for Docker.
