---
layout: page
title: About
permalink: /about/
---

<section class="bio">
  <img class="bio-photo" src="/assets/profile_picture.jpeg" alt="Vidhya Arvind">
  <div class="bio-text">
    <p>
      I'm a <a href="https://www.linkedin.com/in/vidhya-arvind-11908723/">Staff Software Engineer, Data Abstractions</a>
      at Netflix and a founding architect of Netflix's Data Abstraction
      Platform. My team builds the storage primitives — KeyValue, TimeSeries,
      Tree, Graph, Table Metadata, and more — that sit between hundreds of
      Netflix services and the distributed databases that power them.
    </p>
  </div>
</section>

## What I work on

The Data Abstraction Platform decouples application developers from the
specifics of any one database. Behind a small set of clean APIs, the platform
handles partitioning, bucketing, replication, durability, and lifecycle
concerns so product teams can move fast without re-learning Cassandra,
EVCache, Dynomite, or whatever store sits underneath. A few areas I've
focused on:

- **Reliable APIs at petabyte scale.** Idempotent writes, novel bucketing
  algorithms, and table layouts that keep partitions small even when data
  grows unbounded.
- **Beyond durability with Write-Ahead Logging.** A WAL layer that protects
  against multi-partition failures, replication gaps, and silent corruption —
  the kinds of problems that break the assumptions of "the database
  guarantees it."
- **Centralized data deletion.** A platform that handles the end-to-end
  lifecycle of removing user data across heterogeneous stores, from discovery
  through verified deletion.

## Writing

I've authored, co-authored, and contributed to several Netflix TechBlog
posts on the data abstraction platform — Write-Ahead Log resilience, the
Key-Value abstraction (lead author), Data Gateway, and the Graph
abstraction. The full list with summaries lives on the
[writing page](/writing/).

## Speaking

I've spoken at QCon San Francisco, Cassandra Summit, Austin API Summit,
Nordic APIs, the Future of Memory & Storage Summit, and Girl Geek X. The
full list lives on the [talks page](/talks/).

<div class="photo-gallery">
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720330815569/"><img src="/assets/qcon-2025-stage-1.jpg" alt="QCon SF 2025 — Data Deletion at Netflix"></a>
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720330815569/"><img src="/assets/qcon-2025-with-shawn-2.jpg" alt="QCon SF 2025 with Shawn Liu"></a>
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720330815569/"><img src="/assets/qcon-2025-stage-2.jpg" alt="QCon SF 2025"></a>
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720330815569/"><img src="/assets/qcon-2025-with-shawn-1.jpg" alt="QCon SF 2025"></a>
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720322828804/"><img src="/assets/qcon-2024-stage-1.jpg" alt="QCon SF 2024 — Write-Ahead Logging, with Prudhviraj Karumanchi"></a>
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720322828804/"><img src="/assets/qcon-2024-stage-2.jpg" alt="QCon SF 2024"></a>
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720322828804/"><img src="/assets/qcon-2024-stage-3.jpg" alt="QCon SF 2024"></a>
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720322828804/"><img src="/assets/qcon-2024-stage-4.jpg" alt="QCon SF 2024"></a>
</div>

<p class="photo-credit">
  Photos by QCon Pictures
  (<a href="https://www.flickr.com/photos/qconpictures/albums/72177720330815569/">2025</a>,
  <a href="https://www.flickr.com/photos/qconpictures/albums/72177720322828804/">2024</a>).
</p>

## Background

Before Netflix, I worked on storage and platform problems at **Box** and
**Verizon**. I love debugging gnarly distributed-systems failures, designing
APIs that age well, and turning hard storage problems into simple primitives
other engineers can build on.

## Elsewhere

- [GitHub](https://github.com/vidhyaarvind)
- [LinkedIn](https://www.linkedin.com/in/vidhya-arvind-11908723/)
- [Twitter / X](https://twitter.com/vidhyaarvind)
