+++
author = "Ray Tsang"
title = "Deployment & Managing Microservices with Containers and Kubernetes"
description = "Deployment & Managing Microservices with Containers and Kubernetes"
categories = ["Microservices", "Cloud Native"]
tags = ["talk", "java", "microservice", "container", "docker", "kubernetes"]
date = "2015-11-13"
#featured = "pic03.jpg"
#featuredalt = "Pic 3"
featuredpath = "date"
linktitle = ""
type = "post"
+++

## Abstract
A quick overview on Docker containers, usages, and how to scale up from a single container to a fleet of containers working together with Kubernetes for real-life workloads, such as running java-based applications! Join this session to see how to use Kubernetes to launch, manage, and rolling-upgrade a fleet of Java application instances with session replication.

Kubernetes builds on top of Docker to construct a clustered container scheduling service. Kubernetes enables users to ask a cluster to run a set of containers. The system will automatically pick worker nodes to run those containers on, which we think of more as "scheduling" than "orchestration". Kubernetes also provides ways for containers to find and communicate with each other and ways to manage both tightly coupled and loosely coupled sets of cooperating containers.

In this session, you'll learn:
- How to containerize different Java-based microservice workloads using Docker and different build tool plugins
- Deploying and managing a fleet of Java-based microservices in Kubernetes
- Service discovery 101 in Kubernetes
- Perform critical DevOps steps, such as canary, rolling update, roll backs...
- Tips and tricks!

## Videos
{{< youtube kT1vmK0r184 >}}

## Slides
{{< speakerdeck 81e3f2702d7c47bf9d7b1fb788cc9efb >}}

## Links
- [Kubernetes](https://kubernetes.io)
- [Sample Code](https://github.com/saturnism/spring-boot-docker)

