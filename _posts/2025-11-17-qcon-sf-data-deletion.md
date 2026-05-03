---
layout: post
title: "Architecting a Centralized Platform for Data Deletion at Netflix"
date: 2025-11-17 15:55:00 -0800
categories: talks
---

How do you safely manage data deletion across a fleet of diverse data stores,
at Netflix scale? In this QCon San Francisco 2025 talk, Shawn Liu and I
present a centralized, extensible platform that owns the end-to-end data
deletion lifecycle: from identifying data, to executing deletion across
heterogeneous backends, to verifying it actually happened.

We discuss the architecture, the privacy and compliance constraints driving
the design, and the resilience patterns that keep the platform reliable
under failure.

[Talk on QCon SF](https://qconsf.com/presentation/nov2025/architecting-centralized-platform-data-deletion-netflix) ·
[InfoQ write-up](https://www.infoq.com/news/2025/11/netflix-data-deletion/)
