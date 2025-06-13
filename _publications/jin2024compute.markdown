---
layout: publication
title: 'Compute Or Load KV Cache? Why Not Both?'
authors: Shuowei Jin, Xueshen Liu, Qingzhao Zhang, Z. Morley Mao
conference: "Arxiv"
year: 2024
bibkey: jin2024compute
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03065'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs) are increasingly deployed in large-scale online
services, enabling sophisticated applications. However, the computational
overhead of generating key-value (KV) caches in the prefill stage presents a
major bottleneck, particularly for long-context inputs. Prefix caching
mitigates this issue by storing KV caches for reuse, reducing redundant
computation. Despite its advantages, prefix caching suffers from high latency
due to the limited I/O bandwidth of storage devices, constraining inference
efficiency. To address this challenge, we introduce Cake, a novel KV cache
loading system that optimally utilizes both computational and I/O resources in
parallel. Cake employs a bidirectional scheduling strategy that dynamically
balances KV cache computation and loading, ensuring efficient resource
utilization. Additionally, Cake incorporates an adaptive scheduling mechanism
that seamlessly integrates with non-prefix caching requests, improving system
throughput and adapting to fluctuating resource availabilty. Through extensive
evaluations across various hardware configurations, datasets, and storage
conditions, Cake achieves on average 2.6x reduction in Time to First Token
(TTFT) compared to compute-only and I/O-only methods. Our findings highlight
Cake as an effective and practical solution for optimizing long-context LLM
inference, bridging the gap between computation and I/O efficiency in
large-scale AI deployments.
