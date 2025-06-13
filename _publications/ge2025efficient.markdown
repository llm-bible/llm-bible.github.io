---
layout: publication
title: 'Bytescale: Efficient Scaling Of LLM Training With A 2048K Context Length On More Than 12,000 Gpus'
authors: Hao Ge, Junda Feng, Qi Huang, Fangcheng Fu, Xiaonan Nie, Lei Zuo, Haibin Lin, Bin Cui, Xin Liu
conference: "Arxiv"
year: 2025
bibkey: ge2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.21231"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques']
---
Scaling long-context ability is essential for Large Language Models (LLMs).
To amortize the memory consumption across multiple devices in long-context
training, inter-data partitioning (a.k.a. Data Parallelism) and intra-data
partitioning (a.k.a. Context Parallelism) are commonly used. Current training
frameworks predominantly treat the two techniques as orthogonal, and establish
static communication groups to organize the devices as a static mesh (e.g., a
2D mesh). However, the sequences for LLM training typically vary in lengths, no
matter for texts, multi-modalities or reinforcement learning. The mismatch
between data heterogeneity and static mesh causes redundant communication and
imbalanced computation, degrading the training efficiency.
  In this work, we introduce ByteScale, an efficient, flexible, and scalable
LLM training framework for large-scale mixed training of long and short
sequences. The core of ByteScale is a novel parallelism strategy, namely Hybrid
Data Parallelism (HDP), which unifies the inter- and intra-data partitioning
with a dynamic mesh design. In particular, we build a communication optimizer,
which eliminates the redundant communication for short sequences by data-aware
sharding and dynamic communication, and further compresses the communication
cost for long sequences by selective offloading. Besides, we also develop a
balance scheduler to mitigate the imbalanced computation by parallelism-aware
data assignment. We evaluate ByteScale with the model sizes ranging from 7B to
141B, context lengths from 256K to 2048K, on a production cluster with more
than 12,000 GPUs. Experiment results show that ByteScale outperforms the
state-of-the-art training system by up to 7.89x.
