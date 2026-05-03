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

[Video on InfoQ](https://www.infoq.com/presentations/netflix-write-ahead-logging/)
