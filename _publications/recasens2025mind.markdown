---
layout: publication
title: 'Mind The Memory Gap: Unveiling GPU Bottlenecks In Large-batch LLM Inference'
authors: Pol G. Recasens, Ferran Agullo, Yue Zhu, Chen Wang, Eun Kyung Lee, Olivier Tardieu, Jordi Torres, Josep Ll. Berral
conference: "Arxiv"
year: 2025
bibkey: recasens2025mind
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08311'}
tags: ['Reinforcement Learning', 'RAG']
---
Large language models have been widely adopted across different tasks, but
their auto-regressive generation nature often leads to inefficient resource
utilization during inference. While batching is commonly used to increase
throughput, performance gains plateau beyond a certain batch size, especially
with smaller models, a phenomenon that existing literature typically explains
as a shift to the compute-bound regime. In this paper, through an in-depth
GPU-level analysis, we reveal that large-batch inference remains memory-bound,
with most GPU compute capabilities underutilized due to DRAM bandwidth
saturation as the primary bottleneck. To address this, we propose a Batching
Configuration Advisor (BCA) that optimizes memory allocation, reducing GPU
memory requirements with minimal impact on throughput. The freed memory and
underutilized GPU compute capabilities can then be leveraged by concurrent
workloads. Specifically, we use model replication to improve serving throughput
and GPU utilization. Our findings challenge conventional assumptions about LLM
inference, offering new insights and practical strategies for improving
resource utilization, particularly for smaller language models.
