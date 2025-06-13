---
layout: publication
title: 'Slimpipe: Memory-thrifty And Efficient Pipeline Parallelism For Long-context LLM Training'
authors: Zhouyang Li, Yuliang Liu, Wei Zhang, Tailing Yuan, Bin Chen, Chengru Song, Di Zhang
conference: "Arxiv"
year: 2025
bibkey: li2025memory
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14519'}
tags: ['Attention Mechanism', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture']
---
Pipeline Parallelism (PP) serves as a crucial technique for training Large
Language Models (LLMs), owing to its capability to alleviate memory pressure
from model states with relatively low communication overhead. However, in
long-context scenarios, existing pipeline parallelism methods fail to address
the substantial activation memory pressure, primarily due to the peak memory
consumption resulting from the accumulation of activations across multiple
microbatches. Moreover, these approaches inevitably introduce considerable
pipeline bubbles, further hindering efficiency.
  To tackle these challenges, we propose SlimPipe, a novel approach to
fine-grained pipeline parallelism that employs uniform sequence slicing coupled
with one-forward-one-backward (1F1B) schedule. It reduces the accumulated
activations from several microbatches to just one, which is split into several
slices. Although the slices are evenly partitioned, the computation cost is not
equal across slices due to causal attention. We develop a sophisticated
workload redistribution technique to address this load imbalance. SlimPipe
achieves (1) near-zero memory overhead and (2) minimal pipeline bubbles
simultaneously. The effectiveness of SlimPipe has been proven by thorough
testing with diverse model architectures, context window sizes, and
SlimPipe-specific configurations. For example, on the Llama 70B model, compared
to state-of-the-art methods, SlimPipe significantly boosts the Model FLOPs
Utilization (MFU) to up to \\(1.57\times\\) for a context length of 512K. More
notably, for a context length of 2048K, it maintains over 45% utilization on
256 NVIDIA Hopper 80GB GPUs, while other approaches either suffer significant
performance drops or fail entirely due to memory constraints.
