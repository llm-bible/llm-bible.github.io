---
layout: publication
title: 'Accelerating Moe Model Inference With Expert Sharding'
authors: Oana Balmau, Anne-marie Kermarrec, Rafael Pires, André Loureiro Espírito Santo, Martijn De Vos, Milos Vujasinovic
conference: "Arxiv"
year: 2025
bibkey: balmau2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08467"}
tags: ['Reinforcement Learning', 'Training Techniques', 'Fine-Tuning', 'Model Architecture']
---
Mixture of experts (MoE) models achieve state-of-the-art results in language
modeling but suffer from inefficient hardware utilization due to imbalanced
token routing and communication overhead. While prior work has focused on
optimizing MoE training and decoder architectures, inference for encoder-based
MoE models in a multi-GPU with expert parallelism setting remains
underexplored. We introduce MoEShard, an inference system that achieves perfect
load balancing through tensor sharding of MoE experts. Unlike existing
approaches that rely on heuristic capacity factors or drop tokens, MoEShard
evenly distributes computation across GPUs and ensures full token retention,
maximizing utilization regardless of routing skewness. We achieve this through
a strategic row- and column-wise decomposition of expert matrices. This reduces
idle time and avoids bottlenecks caused by imbalanced expert assignments.
Furthermore, MoEShard minimizes kernel launches by fusing decomposed expert
computations, significantly improving throughput. We evaluate MoEShard against
DeepSpeed on encoder-based architectures, demonstrating speedups of up to
6.4\\(\times\\) in time to first token (TTFT). Our results show that tensor
sharding, when properly applied to experts, is a viable and effective strategy
for efficient MoE inference.
