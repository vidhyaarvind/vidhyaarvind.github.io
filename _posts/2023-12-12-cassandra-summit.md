---
layout: post
title: "How Netflix Delivers Key-Value and Time-Series Storage at Any Scale"
date:   2023-12-12 16:51:11 -0700
categories: talks
---

At Netflix, Apache Cassandra's bread and butter workloads are wide-column storage for Key-Value and Time-Series use cases, but for those that operate at scale they know that if you just structure your tables naively your clusters will become unstable as partitions or columns grow in size. In this talk, we show how to design reliable APIs and lay out Key-Value and Time-Series data in Apache Cassandra for petabyte scale datasets. For example, most Key-Value data is small, but for large partitions we present a novel technique to dynamically bucket data, providing users with fast access for small data and linearly scalable latency for large values. Next, we will show how to lay out Time-Series datasets with table sharding, time and random bucketing so that large partitions are automatically split while maintaining aggressive latency goals. In addition, since we use tables for data expiration rather than compaction, we can get up to 2x more storage out of the same disk space. By combining fully-idempotent APIs, novel table layouts, bucketing algorithms, and compression schemes Netflix has been able to scale Apache Cassandra usage orders of magnitude further than we could before.

[Slides](/assets/cassandra_summit_how_netflix_delivers_key_value_and_time_series_storages_at_any_scale.pdf)

[![Cassandra Summit 2023](http://img.youtube.com/vi/sQ-_jFgOBng/0.jpg)](https://www.youtube.com/watch?v=sQ-_jFgOBng&t=1s "Cassandra Summit 2023")

