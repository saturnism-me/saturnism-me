+++
author = "Ray Tsang"
title = "Fast and Efficient Microservices with gRPC"
description = "Fast and Efficient Microservices with gRPC"
categories = ["Microservices", "Cloud Native"]
tags = ["talk", "java", "microservice", "grpc", "protocol", "rest", "json"]
date = "2017-04-11"
linktitle = ""
type = "talk"
aliases = [
  "/talk/fast-efficient-microservices",
  "/talk/grpc-101"
]
+++

## Abstract
gRPC is a high performance, open source, general RPC framework that puts mobile and HTTP/2 first. gRPC is based on many years of Google's experience in building distributed systems - it is designed to be low latency, bandwidth and CPU efficient, to create massively distributed systems that span data centers, as well as power mobile apps, real-time communications, IoT devices and APIs. It's also interoperable between multiple languages.

But beyond that fact that it's more efficient than REST, we'll look into how to use gRPC's streaming API, where you can establish server-side streaming, client-side streaming, and bidirectional streaming! This allows developers to build sophisticated real-time applications with ease.

In addition to learning about gRPC and HTTP/2 concepts with code and demonstrations to see how to:
- Configuring projects to generate gRPC stub code with Maven and Gradle
- Using Protobuf3 to define services
- Creating synchronous and asynchronous services, with streaming
- Load balancing

## Videos
{{< youtube DU-q5kOf2Rc >}}

## Slides
{{< speakerdeck d09fe2ef925d4f1387b51e71a713dee6 >}}

## Feedback
Your feedback is important, please take a momement to let me know how I did and what I can improve on!

- {{< typeform-popup K01lSP saturnism >}}

## Links
- [gRPC](https://grpc.io)
- [Sample Code](https://github.com/saturnism/grpc-java-by-example)
- [gRPC Contrib by Salesforce - Spring Boot Starter, Java 8 Stubs](https://github.com/salesforce/grpc-java-contrib)
- [Reactive gRPC by Salesforce - RxJava2, Spring Reactor](https://github.com/salesforce/reactive-grpc)
