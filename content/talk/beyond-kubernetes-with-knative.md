+++
author = "Ray Tsang"
title = "Beyond Kubernetes - Serverless with Knative, riff, and Spring Cloud Function"
description = "Beyond Kubernetes - Serverless with Knative, riff, and Spring Cloud Function"
categories = ["Microservices", "Cloud Native", "Serverless"]
tags = ["talk", "java", "microservice", "serverless", "service-mesh", "kubernetes", "istio"]
date = "2018-11-13"
linktitle = ""
type = "talk"
aliases = [
  "/talk/knative-101"
]
+++

## Abstract
From function source code to running in Kubernetes in 5 minutes. That's the power some of the latest open source projects can bring to your fingertips. This perceived simplicity actually hides layers of abstractions underneath. In this deep dive, we'll explore all the technology behind the scenes, from Kubernetes, Istio, Knative, to riff and Spring Cloud function.

We'll explore how Istio and Knative extend Kubernetes via Custom Resource Definitions to provide support for higher level developer concerns such as microservices autoscaling, routing across revisions of an application, and a unified eventing bus to compose event-driven workloads. Building on top of this, we'll take a look at how riff has been replatformed to run on top of Knative, while preserving its scale-on-demand Function as a Service ease of use. Finally, to tie the platform from top to bottom, we'll dive into Spring Cloud Function to see how to use Function interface to create a function that can process both synchronous HTTP requests as well as event-based messages using riff and Knative.

## Code Labs
- [Knative and Riff with Spring Boot](http://bit.ly/spring-riff-lab)
- [Kubernetes with Spring Boot](http://bit.ly/k8s-lab)
- [Istio with Spring Boot](http://bit.ly/istio-lab)

## Slides
{{< speakerdeck e064160afbe14a78ab825333ff6bf223 >}}

## Videos
{{< youtube HEWb1IWqT30 >}}


## Links
- [Knative](https://github.com/knative/docs)
- [Istio](https://istio.io)
- [Kubernetes](https://kubernetes.io)

## Feedback
Your feedback is important, please take a momement to let me know how I did and what I can improve on!

- {{< typeform-popup K01lSP saturnism >}}


