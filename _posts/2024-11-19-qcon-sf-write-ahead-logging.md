---
layout: post
title: "Beyond Durability: Database Resilience with Write-Ahead Logging at Netflix"
date: 2024-11-19 10:35:00 -0800
categories: talks
---

Modern database durability guarantees are often insufficient during extended
system outages or data corruption scenarios. In this QCon San Francisco 2024
talk I walk through Netflix's journey to enhanced data durability and
reliability through a Write-Ahead Logging (WAL) layer that sits above our
data stores.

The talk covers how WAL addresses critical challenges like data loss,
corruption, multi-partition mutations, and replication gaps — and the
strategic trade-offs we considered when designing for Netflix's scale.

Co-presented with Prudhviraj Karumanchi.

[Video on InfoQ](https://www.infoq.com/presentations/netflix-write-ahead-logging/)

<div class="photo-grid">
  <figure>
    <img src="/assets/qcon-2024-stage-1.jpg" alt="Vidhya Arvind and Prudhviraj Karumanchi on stage at QCon SF 2024">
    <figcaption>On stage with Prudhviraj Karumanchi</figcaption>
  </figure>
  <figure>
    <img src="/assets/qcon-2024-stage-2.jpg" alt="QCon SF 2024 — WAL talk">
    <figcaption>QCon SF 2024 &middot; Ballroom A</figcaption>
  </figure>
  <figure>
    <img src="/assets/qcon-2024-stage-3.jpg" alt="QCon SF 2024 — WAL talk">
    <figcaption>Mid-talk</figcaption>
  </figure>
  <figure>
    <img src="/assets/qcon-2024-stage-4.jpg" alt="QCon SF 2024 — WAL talk">
    <figcaption>Audience Q&amp;A</figcaption>
  </figure>
</div>

<p class="photo-credit">
  Photos by <a href="https://www.flickr.com/photos/qconpictures/albums/72177720322828804/">QCon Pictures</a>.
</p>
