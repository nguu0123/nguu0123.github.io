---
title: "Supporting Opportunistic Data Operations for Data-Intensive Computational Applications"
collection: publications
category: workshop
# permalink: /publication/05-12-2025-supporting-opportunistic-data-operations.md
excerpt: ""
date: 2024-12-05
venue: "The Seventh IEEE International Workshop on Benchmarking, Performance Tuning and Optimization for Big Data Applications (BPOD 2024)"
paperurl: "https://ieeexplore.ieee.org/abstract/document/10826079"
author: "Minh-Tri Nguyen; <b>Anh-Dung Nguyen</b>; Jarno Rantaharju; Touko Puro; Matthias Rheinhardt; Maarit Korpi-Lagg; Hong-Linh Truong"
code: https://github.com/rdsea/odop
# citation: 'M. -T. Nguyen et al., "Supporting Opportunistic Data Operations for Data-Intensive Computational Applications," 2024 IEEE International Conference on Big Data (BigData), Washington, DC, USA, 2024, pp. 3735-3744, doi: 10.1109/BigData62323.2024.10826079'
---

A long running data-intensive computational application acquires costly computing resources. With the emerging new architectures, like computing systems with multiple nodes of many-core CPUs and accelerators, while domain-specific tools and libraries employed in such an application leverage high parallelism on accelerators for intensive computations, the remaining resources can potentially be utilized for other application-related data operations. Such data operations, called opportunistic data operations in this work, must usually be carried out for post-processing or follow-up analytics based on results produced during the runtime of the application. These operations are not easily backfilled or preempted under the guidance of the domain scientist or by common task scheduling systems due to their complex dependencies.In this paper, we introduce a framework for domain scientists to identify and execute opportunistic data operation tasks. With a minimal specification or modification of the main application, the scientists can specify, monitor, and execute opportunistic tasks independently from the main application and the framework will detect underutilized resources to execute these tasks, thereby, optimizing utilization efficiency within the allocated resources. We present experiments to demonstrate the applicability of our framework on a magnetic field modeling running on the LUMI computing system.
