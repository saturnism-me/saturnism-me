+++
author = "Ray Tsang"
title = "Making Microservices Micro with Istio and Kubernetes"
description = "Making Microservices Micro with Istio and Kubernetes"
categories = ["Microservices", "Cloud Native"]
tags = ["talk", "java", "microservice", "service-mesh", "kubernetes", "istio"]
date = "2017-11-28"
#featured = "pic03.jpg"
#featuredalt = "Pic 3"
featuredpath = "date"
linktitle = ""
type = "post"
+++

## Abstract
Microservices are here to stay. When applied properly, microservices techniques and culture ultimately help us continuously improve business at a faster pace than traditional architecture. However, microservices architecture itself can be complex to configure. All of a sudden, we are faced with the need for a service discovery server, how do we store service metadata, make decisions on whether to use client side load balancing or server side load balancing, deal with network resiliency, think how do we enforce service policies and audit, trace nested services calls.... The list goes on.

Sure, it's easy to have a single stack that makes everything work provided there are good microservices support - but what if you have a polyglot environment? How would you make sure all of the stack can address the same concerns in a consistent way? This is where a service mesh comes in.

In this talk, Ray will introduce Istio, an open source service mesh framework created by Google, IBM, and Lyft. We'll see how the service mesh work, the technology behind it, and how it addresses aforementioned concerns.

## Videos
{{< youtube AGztKw580yQ >}}

## Slides
{{< speakerdeck bf2f37c2a59a48039de097d18d20e7eb >}}

## Links
- [Istio](https://istio.io)
- [Kubernetes](https://kubernetes.io)
- [Sample Code](https://github.com/saturnism/istio-by-example-java)
- [Workshop](https://github.com/saturnism/istio-workshop)

