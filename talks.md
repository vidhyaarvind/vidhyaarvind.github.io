---
layout: page
title: Talks
permalink: /talks/
---

A selection of public talks on data abstractions, distributed databases,
and platform engineering at Netflix.

<ul class="talks-list">

  <li>
    <span class="talk-year">2025</span>
    <div>
      <span class="talk-venue">QCon San Francisco</span>
      <a class="talk-title" href="https://qconsf.com/presentation/nov2025/architecting-centralized-platform-data-deletion-netflix">
        Architecting a Centralized Platform for Data Deletion at Netflix
      </a>
      <p>How Netflix safely manages data deletion across diverse data stores at scale — from identifying the data to verifying and executing deletion through a centralized, extensible platform. With Shawn Liu.</p>
      <p class="talk-links">
        <a href="https://qconsf.com/presentation/nov2025/architecting-centralized-platform-data-deletion-netflix">Talk page</a>
        <a href="https://www.infoq.com/news/2025/11/netflix-data-deletion/">InfoQ write-up</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2025</span>
    <div>
      <span class="talk-venue">Apache Cassandra Meetup &middot; hosted by Uber</span>
      <a class="talk-title" href="{{ '/2025/08/12/uber-cassandra-meetup-load-shedding/' | relative_url }}">
        Resilient Cassandra: Intelligent Backpressure Using Resource Utilization and Queueing Metrics
      </a>
      <p>How to protect Cassandra from overload with backpressure that goes beyond CPU and latency — using PSI (Pressure Stall Information) queueing metrics normalized by QPS to detect genuine resource strain and shed load intelligently, without rejecting requests during normal latency variation.</p>
      <p class="talk-links">
        <a href="https://www.youtube.com/watch?v=kU1Ri0KDS7M">Video</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2024</span>
    <div>
      <span class="talk-venue">Apache Cassandra Bay Area Meetup &middot; hosted at Netflix</span>
      <a class="talk-title" href="{{ '/2024/10/11/netflix-cassandra-meetup-tombstones-backpressure/' | relative_url }}">
        How Netflix Handles C* Tombstones at Scale &amp; SLO-based Data Retrieval and Back Pressure
      </a>
      <p>Two-in-one talk at the Apache Cassandra Bay Area meetup hosted at Netflix's Los Gatos campus: how the data platform manages tombstones at petabyte scale, and how SLO-driven data retrieval and back pressure keep Cassandra responsive under load.</p>
      <p class="talk-links">
        <a href="https://www.youtube.com/watch?v=n_SXhW-x0WA">Video</a>
        <a href="https://www.meetup.com/apache-cassandra-bay-area/events/303469006/">Meetup page</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2024</span>
    <div>
      <span class="talk-venue">QCon San Francisco</span>
      <a class="talk-title" href="https://www.infoq.com/presentations/netflix-write-ahead-logging/">
        Beyond Durability: Database Resilience and Entropy Reduction with Write-Ahead Logging at Netflix
      </a>
      <p>Modern database durability guarantees aren't enough during extended outages or corruption. This talk presents Netflix's WAL architecture for surviving data loss, multi-partition mutations, and replication gaps.</p>
      <p class="talk-links">
        <a href="https://www.infoq.com/presentations/netflix-write-ahead-logging/">Video / InfoQ</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2024</span>
    <div>
      <span class="talk-venue">Future of Memory &amp; Storage Summit</span>
      <a class="talk-title" href="https://files.futurememorystorage.com/proceedings/2024/20240806_DCTR-103-1_Arvind.pdf">
        Decoupling Services from Storage Engines Through Data Abstractions at Netflix
      </a>
      <p>Why Netflix built abstraction layers between application services and storage engines, and what the platform looks like in production.</p>
      <p class="talk-links">
        <a href="https://files.futurememorystorage.com/proceedings/2024/20240806_DCTR-103-1_Arvind.pdf">Slides (PDF)</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2024</span>
    <div>
      <span class="talk-venue">Austin API Summit / Nordic APIs</span>
      <a class="talk-title" href="{{ '/2024/03/12/austin-api-summit/' | relative_url }}">
        How Netflix Uses Data Abstraction to Operate 100s of Use-Cases
      </a>
      <p>How a control plane and data plane abstract storage, and the techniques that let the service safely scale to hundreds of instances.</p>
      <p class="talk-links">
        <a href="/assets/austin_summit_how_netflix_uses_data_abstraction_to_operate_100s_of_use_cases.pdf">Slides</a>
        <a href="https://www.youtube.com/watch?v=XKPOr-7loBo">Video</a>
        <a href="https://nordicapis.com/how-netflix-scales-using-data-abstraction/">Write-up</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2023</span>
    <div>
      <span class="talk-venue">Cassandra Summit</span>
      <a class="talk-title" href="{{ '/2023/12/12/cassandra-summit/' | relative_url }}">
        How Netflix Delivers Key-Value and Time-Series Storage at Any Scale
      </a>
      <p>Designing reliable APIs and table layouts on Apache Cassandra for petabyte-scale Key-Value and Time-Series workloads, including dynamic bucketing for unbounded partitions.</p>
      <p class="talk-links">
        <a href="/assets/cassandra_summit_how_netflix_delivers_key_value_and_time_series_storages_at_any_scale.pdf">Slides</a>
        <a href="https://www.youtube.com/watch?v=sQ-_jFgOBng">Video</a>
      </p>
    </div>
  </li>

  <li>
    <span class="talk-year">2021</span>
    <div>
      <span class="talk-venue">Science Olympiad</span>
      <a class="talk-title" href="{{ '/2021/03/16/science-olympiad/' | relative_url }}">
        Propeller Propulsion — Science Olympiad
      </a>
      <p>An aside.</p>
    </div>
  </li>

</ul>
