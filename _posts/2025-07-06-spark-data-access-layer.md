---
layout: post
author: "Mahdi Mohseni"
title: "Data Access Layer Abstraction with Apache Spark"
date: 2025-07-06
tags: ["Spark", 
"PySpark", 
"Object_Relational_Mapping", 
"SQLalchemy"
]
description: "How do you build data processing systems that serve multiple customers with varying storage, compute, and scaling need, without rewriting your core logic each time? In this post, I show how Apache Spark can be used not just for large-scale data processing, but also as an abstraction layer for data access. This approach helps simplify architecture, isolate customer-specific differences, and reduce onboarding and maintenance costs, based on hands-on insights from real projects."
draft: false
---


Some data processing applications serve multiple customers with similar workflows. While the core processes may be comparable, customer-specific requirements—such as compute environments, storage backends, and data volumes—can differ significantly. This variation demands a flexible architecture that reduces maintenance overhead and enables efficient onboarding of new clients.

Apache Spark is well-suited to the computational challenges of such systems, offering robust support for large-scale, distributed processing in diverse environments. For other concerns—like interoperability with heterogeneous storage systems or scalability across workloads—abstracting the data access layer becomes essential. This abstraction simplifies adaptation to evolving requirements and makes it easier to integrate new customers with minimal changes to the core logic.

In this post, I’ll walk through how Spark can support such an architecture, including lessons learned from real-world projects.

[Read more ...](https://medium.com/@mohsenim/data-access-layer-abstraction-with-apache-spark-f6d2b8bbe2d4)
