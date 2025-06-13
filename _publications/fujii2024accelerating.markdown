---
layout: publication
title: 'Accelerating Large Language Model Training With 4D Parallelism And Memory Consumption Estimator'
authors: Kazuki Fujii, Kohei Watanabe, Rio Yokota
conference: "Arxiv"
year: 2024
bibkey: fujii2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06465"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Large-Scale Training', 'Fine-Tuning']
---
In large language model (LLM) training, several parallelization strategies,
including Tensor Parallelism (TP), Pipeline Parallelism (PP), Data Parallelism
(DP), as well as Sequence Parallelism (SP) and Context Parallelism (CP), are
employed to distribute model parameters, activations, and optimizer states
across devices. Identifying the optimal parallelization configuration for each
environment while avoiding GPU memory overflow remains a challenging task. In
this study, we provide precise formulas to estimate the memory consumed by
parameters, gradients, optimizer states, and activations for 4D parallel
training (DP, TP, PP, CP) in the Llama architecture. We conducted 454
experiments on A100 and H100 GPUs, incorporating often neglected factors such
as temporary buffers and memory fragmentation into our analysis. Results
indicate that when the estimated memory usage is below 80% of the available
GPU memory, the training never encounters out-of-memory errors. This simple yet
effective formula allows us to identify parallelization configurations that
could lead to memory overflow in advance, significantly reducing the
configuration search space. Additionally, through a comprehensive exploration
of optimal configurations in 4D parallelism, our analysis of the 454
experimental results provides empirical insights into optimal 4D parallelism
configurations.
