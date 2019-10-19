+++
author = "Ray Tsang"
title = "Spring (or Java) to Kubernetes Faster and Easier"
description = "Kubernetes Best Practices - Spring (or Java) to Kubernetes Faster and Easier"
categories = ["Microservices", "Cloud Native"]
tags = ["talk", "java", "microservice", "spring", "kubernetes", "container", "docker"]
date = "2019-10-08"
linktitle = ""
type = "talk"
aliases = [
  "/talk/kubernetes-best-practices"
]
+++

## Abstract
For Spring and Java developers, building containers is a common obstacle on the road to Kubernetes adoption. Traditionally, Dockerfiles define container builds imperatively, but can also be cumbersome, error-prone, and slow. The development cycle can be slow. IDE support is generally poor. Most likely, your Java application will crash with an OOMKill message.

In this talk, we'll introduce tools and best practices to help you adopt Kubernetes faster and easier. This includes tools such as Jib and Skaffold for fast image build and development cycle turnaround time. We'll also discuss best practices for configuring your Java applications to run inside of Kubernetes, such as health checks, zero downtime deployment, externalizing configurations, logging, and understanding memory usage to avoid OOMKilled situations.

## Videos
{{< youtube YTPUNesUIbI >}}

## Slides
{{< speakerdeck ab93216f9a014144845ce3701c696bfd >}}

## Feedback
Your feedback is important, please take a momement to let me know how I did and what I can improve on!

- {{< typeform-popup K01lSP saturnism >}}

## Links
- [Google Cloud Native with Spring Boot Presentation](/talk/google-cloud-native-spring-boot-kubernetes)
- [Spring Cloud GCP Homepage](http://cloud.spring.io/spring-cloud-gcp)
- [Short Code Labs](http://g.co/codelabs/spring)
- [Long Code Lab](http://bit.ly/spring-gcp-lab)
- [Spring PetClinic GCP Sample Code](https://github.com/saturnism/spring-petclinic-gcp/)
