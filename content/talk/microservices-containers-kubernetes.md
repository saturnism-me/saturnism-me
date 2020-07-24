+++
author = "Ray Tsang"
title = "Deploying & Managing Microservices with Containers and Kubernetes"
description = "Deploying & Managing Microservices with Containers and Kubernetes"
categories = ["Microservices", "Cloud Native"]
tags = ["talk", "java", "microservice", "container", "docker", "kubernetes"]
date = "2015-11-13"
linktitle = ""
type = "talk"
aliases = [
  "/talk/kubernetes-101"
]
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

## Code Labs / Samples
- [Kubernetes with Spring Boot](http://bit.ly/k8s-lab)
- [Container and Kubernetes by Examples with Spring Boot](https://github.com/saturnism/docker-kubernetes-by-example-java)

## Slides
{{< speakerdeck 81e3f2702d7c47bf9d7b1fb788cc9efb >}}

## Videos
{{< youtube kT1vmK0r184 >}}

## Links
- [Kubernetes](https://kubernetes.io)

## Events
- 2015 OSCON
- [2015 SpringOne](https://www.youtube.com/watch?v=Bcs-inRnLDc)
- [2015 J-Fall](https://www.youtube.com/watch?v=0mIwhAJz2Gg)
- [2015 Devoxx Belgium](https://www.youtube.com/watch?v=kT1vmK0r184)
- [2016 Devoxx Poland](https://www.youtube.com/watch?v=Z_gzl8RqZuE)
- [2016 JFokus](https://www.youtube.com/watch?v=R2l-tL_1els)
- [2016 vJUG 24](https://www.youtube.com/watch?v=27PExjWv6GY)
- [2016 Voxxed Day Ticino](https://www.youtube.com/watch?v=4ZLVAymNA80)
- [2016 GOTO Amsterdam](https://www.youtube.com/watch?v=8qSpvRKrgHk)
- [2016 Devoxx Belgium](https://www.youtube.com/watch?v=hvfr_g4sBWY)

## Feedback
Your feedback is important, please take a momement to let me know how I did and what I can improve on!

- {{< typeform-popup K01lSP saturnism >}}                                                         


