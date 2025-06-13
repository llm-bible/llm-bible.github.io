---
layout: publication
title: 'TAGC: Optimizing Gradient Communication In Distributed Transformer Training'
authors: Igor Polyakov, Alexey Dukhanov, Egor Spirin
conference: "EuroMLSys 25 Proceedings of the 5th Workshop on Machine Learning and Systems. 2025. 254-260"
year: 2025
bibkey: polyakov2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05638"}
  - {name: "Code", url: "https://github.com/ipolyakov/TAGC"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Large-Scale Training', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
The increasing complexity of large language models (LLMs) necessitates
efficient training strategies to mitigate the high computational costs
associated with distributed training. A significant bottleneck in this process
is gradient synchronization across multiple GPUs, particularly in the
zero-redundancy parallelism mode. In this paper, we introduce Transformer-Aware
Gradient Compression (TAGC), an optimized gradient compression algorithm
designed specifically for transformer-based models. TAGC extends the lossless
homomorphic compression method by adapting it for sharded models and
incorporating transformer-specific optimizations, such as layer-selective
compression and dynamic sparsification. Our experimental results demonstrate
that TAGC accelerates training by up to 15% compared to the standard Fully
Sharded Data Parallel (FSDP) approach, with minimal impact on model quality. We
integrate TAGC into the PyTorch FSDP framework, the implementation is publicly
available at https://github.com/ipolyakov/TAGC.
