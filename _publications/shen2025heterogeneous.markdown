---
layout: publication
title: 'Accelgen: Heterogeneous Slo-guaranteed High-throughput LLM Inference Serving For Diverse Applications'
authors: Haiying Shen, Tanmoy Sen
conference: "Arxiv"
year: 2025
bibkey: shen2025heterogeneous
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13737'}
tags: ['Reinforcement Learning', 'Prompting', 'Applications', 'ACL']
---
In this paper, we consider a mixed-prompt scenario for a large language model
(LLM) inference serving system that supports diverse applications with both
short prompts and long prompts and heterogeneous SLOs for iteration time. To
improve throughput when handling long prompts, previous research introduces a
chunking method, but has not addressed heterogeneous SLOs. To address the
limitation, we propose AccelGen, a high-throughput LLM inference serving system
with heterogeneous SLO guarantees for diverse applications. AccelGen introduces
four core components: (1) SLO-guaranteed dynamic chunking, which dynamically
adjusts chunk sizes to maximize GPU compute utilization while meeting
iteration-level SLOs; (2) Iteration-level SLO-based task prioritization, which
prioritizes tight-SLO requests and batches requests with similar SLOs; (3)
Multi-resource-aware batching, which selects queued requests to maximize the
utilizations of both GPU compute resource and key-value cache (KVC).
Trace-driven real experiments demonstrate that AccelGen achieves 1.42-11.21X
higher throughput, 1.43-13.71X higher goodput, 37-90% higher SLO attainment,
and 1.61-12.22X lower response latency compared to the state-of-the-art
approaches. It achieves performance near the Oracle, which optimally maximizes
goodput.
