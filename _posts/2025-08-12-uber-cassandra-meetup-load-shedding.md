---
layout: post
title: "Resilient Cassandra: Intelligent Backpressure Using Resource Utilization and Queueing Metrics"
date: 2025-08-12 17:30:00 -0700
categories: talks
---

A talk at the Apache Cassandra Meetup hosted by Uber Engineering in
Sunnyvale on August 12, 2025.

Protecting Cassandra from overload is harder than it looks. CPU and
latency are noisy signals — they punish the cluster for normal traffic
shape and ignore real resource starvation. In this talk I walk through a
backpressure system built on Cassandra's internal resource utilization
metrics — specifically **PSI (Pressure Stall Information) queueing data,
normalized by QPS** — to detect genuine resource strain and trigger
intelligent load shedding, without rejecting requests during normal
latency variation.

The system has been used at Netflix to keep mission-critical
Cassandra-based infrastructure stable under load while keeping rejection
rates low for healthy traffic.

[Video on YouTube](https://www.youtube.com/watch?v=kU1Ri0KDS7M)
