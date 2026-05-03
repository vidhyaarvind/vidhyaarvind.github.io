---
layout: page
title: Writing
permalink: /writing/
---

A selection of posts on the Netflix TechBlog about the platform that powers
hundreds of mission-critical use cases at Netflix — the abstractions on top
of distributed databases, the resilience layer that protects the data tier,
and the design choices that let thousands of internal developers work with
one consistent API instead of a different storage engine per team.

Each entry notes my role on the post and what the post is about.

<ul class="talks-list">

  <li>
    <span class="talk-year">2025</span>
    <div>
      <span class="talk-venue">Netflix TechBlog &middot; co-author</span>
      <a class="talk-title" href="https://netflixtechblog.com/building-a-resilient-data-platform-with-write-ahead-log-at-netflix-127b6712359a">
        Building a Resilient Data Platform with Write-Ahead Log at Netflix
      </a>
      <p>How Netflix's Write-Ahead Log layer protects the data tier from the failure modes that slip past normal database durability — multi-partition mutations, replication gaps, silent corruption, extended outages — and the architectural choices that keep it efficient at platform scale.</p>
      <p class="talk-links">
        <a href="https://netflixtechblog.com/building-a-resilient-data-platform-with-write-ahead-log-at-netflix-127b6712359a">Read on Netflix TechBlog</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2024</span>
    <div>
      <span class="talk-venue">Netflix TechBlog &middot; lead author</span>
      <a class="talk-title" href="https://netflixtechblog.com/introducing-netflixs-key-value-data-abstraction-layer-1ea8a0a11b30">
        Introducing Netflix's Key-Value Data Abstraction Layer
      </a>
      <p>The Key-Value abstraction is a generic, reliable API on top of multiple storage engines (Cassandra, EVCache, RocksDB, and more). This post walks through the design — chunked values, dynamic bucketing for unbounded partitions, idempotent writes, and the platform features that let thousands of developers consume KV without learning any one database.</p>
      <p class="talk-links">
        <a href="https://netflixtechblog.com/introducing-netflixs-key-value-data-abstraction-layer-1ea8a0a11b30">Read on Netflix TechBlog</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2024</span>
    <div>
      <span class="talk-venue">Netflix TechBlog &middot; co-author</span>
      <a class="talk-title" href="https://netflixtechblog.com/data-gateway-a-platform-for-growing-and-protecting-the-data-tier-f1ed8db8f5c6">
        Data Gateway: A Platform for Growing and Protecting the Data Tier
      </a>
      <p>Data Gateway is the platform Netflix uses to ship online data access layers — secure, gRPC/HTTP-fronted services that sit between application code and the underlying stores. The post covers why we centralized it, the resilience primitives baked in (circuit breaking, back-pressure, load shedding), and how it became the foundation for the higher-level abstractions like KV, TimeSeries, and Graph.</p>
      <p class="talk-links">
        <a href="https://netflixtechblog.com/data-gateway-a-platform-for-growing-and-protecting-the-data-tier-f1ed8db8f5c6">Read on Netflix TechBlog</a>
      </p>
    </div>
  </li>

</ul>

## Contributions

Posts where I'm acknowledged in the thanks section rather than the byline —
work I helped shape but didn't write up.

<ul class="talks-list">

  <li>
    <span class="talk-year">2026</span>
    <div>
      <span class="talk-venue">Netflix TechBlog &middot; contributor</span>
      <a class="talk-title" href="https://netflixtechblog.com/high-throughput-graph-abstraction-at-netflix-part-i-e88063e6f6d5">
        High-Throughput Graph Abstraction at Netflix: Part I
      </a>
      <p>Netflix's Graph Abstraction handles ~10M ops/sec across 650TB of strongly-typed graph data with low latency. Part I walks through the architecture — built on top of the Key-Value and TimeSeries abstractions — and the use cases driving it (real-time distributed graph, social graph for Netflix Gaming, service topology).</p>
      <p class="talk-links">
        <a href="https://netflixtechblog.com/high-throughput-graph-abstraction-at-netflix-part-i-e88063e6f6d5">Read on Netflix TechBlog</a>
      </p>
    </div>
  </li>

</ul>
