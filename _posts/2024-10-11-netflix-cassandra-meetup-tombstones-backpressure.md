---
layout: post
title: "How Netflix Handles C* Tombstones at Scale & SLO-based Data Retrieval and Back Pressure"
date: 2024-10-11 17:00:00 -0700
categories: talks
---

A talk at the Apache Cassandra Bay Area meetup, hosted at Netflix's Los
Gatos campus on October 11, 2024. Two topics in one slot:

- **Tombstones at scale** — what tombstones cost when you're operating
  petabyte-scale Cassandra clusters across hundreds of use cases, and the
  techniques the Data Abstraction platform uses to keep them under
  control.
- **SLO-based data retrieval and back pressure** — how Netflix uses
  service-level objectives, not raw timeouts, to drive read paths and
  to push back on overloaded clusters before they tip over.

The full meetup also featured Chris Lohfink (Netflix) & Jaydeepkumar
Chovatia (Uber) on incremental repair scheduling, Patrick McFadin
(DataStax) on vector search in Cassandra 5, and Dinesh Joshi (Apple) on
secure analytics with the Cassandra Sidecar.

[Video on YouTube](https://www.youtube.com/watch?v=n_SXhW-x0WA) ·
[Meetup page](https://www.meetup.com/apache-cassandra-bay-area/events/303469006/)
