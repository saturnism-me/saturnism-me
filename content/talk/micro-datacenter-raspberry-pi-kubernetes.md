+++
author = "Ray Tsang"
title = "Micro-datacenter with Raspberry Pi and Kubernetes"
description = "A talk on building a Raspberry Pi cluster to run Kubernetes"
categories = ["Microservices", "Cloud Native"]
tags = ["talk", "java", "microservice", "container", "docker", "kubernetes"]
date = "2016-01-31"
#featured = "pic03.jpg"
#featuredalt = "Pic 3"
featuredpath = "date"
linktitle = ""
type = "post"
+++

## Abstract
Kubernetes is a powerful, open source, container orchestration / cluster management tool created by Google. It drew upon all the lessons learned from a near-decade of using containers at Google. Kubernetes handles a number of failure scenarios gracefully, from a crashed process, to a failure of a cluster node. We'll show this through a real Raspberry Pi computing cluster that runs Kubernetes - and play a real-life chaos monkey by pulling the plugs!

In this session, we'll look beyond container orchestration with Kubernetes, but also demonstrate its failure handling by pulling the plugs on random nodes from a Raspberry Pi computing cluster: - Overview of Kubernetes - Process resource isolation to prevent a run-away process affecting another - Use Replication controller to ensure a crashed process is restarted - Who wants to pull a network or power plug from a computing cluster?

## Videos
{{< youtube iy29zElB4dc >}}


## Links
- [Kubernetes](https://kubernetes.io)
- [Everything you need to know about the Kubernetes Raspberry Pi cluster](https://medium.com/google-cloud/everything-you-need-to-know-about-the-kubernetes-raspberry-pi-cluster-2a2413bfa0fa)
- [Kubernetes Raspberry Pi Cluster —The Story](https://medium.com/google-cloud/kubernetes-raspberry-pi-cluster-the-story-ace773cf8573)
- [Raspberry Pi Cluster Shopping List](http://blog.kubernetes.io/2015/11/creating-a-Raspberry-Pi-cluster-running-Kubernetes-the-shopping-list-Part-1.html)

## Events
- [2016 FOSDEM](https://archive.fosdem.org/2016/schedule/event/kubernetes/)
