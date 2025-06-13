---
layout: publication
title: 'Context Parallelism For Scalable Million-token Inference'
authors: Amy Yang, Jingyi Yang, Aya Ibrahim, Xinfeng Xie, Bangsheng Tang, Grigory Sizov, Jeremy Reizenstein, Jongsoo Park, Jianyu Huang
conference: "Arxiv"
year: 2024
bibkey: yang2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01783"}
tags: ['Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Attention Mechanism']
---
We present context parallelism for long-context large language model
inference, which achieves near-linear scaling for long-context prefill latency
with up to 128 H100 GPUs across 16 nodes. Particularly, our method achieves 1M
context prefill with Llama3 405B model in 77s (93% parallelization efficiency,
63% FLOPS utilization) and 128K context prefill in 3.8s. We develop two
lossless exact ring attention variants: pass-KV and pass-Q to cover a wide
range of use cases with the state-of-the-art performance: full prefill,
persistent KV prefill and decode. Benchmarks on H100 GPU hosts inter-connected
with RDMA and TCP both show similar scalability for long-context prefill,
demonstrating that our method scales well using common commercial data center
with medium-to-low inter-host bandwidth.
