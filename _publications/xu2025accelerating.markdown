---
layout: publication
title: 'Specee: Accelerating Large Language Model Inference With Speculative Early Exiting'
authors: Jiaming Xu, Jiayi Pan, Yongkang Zhou, Siming Chen, Jinhao Li, Yaoxiu Lian, Junyi Wu, Guohao Dai
conference: "Arxiv"
year: 2025
bibkey: xu2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08850"}
tags: ['Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Quantization']
---
Early exiting has recently emerged as a promising technique for accelerating
large language models (LLMs) by effectively reducing the hardware computation
and memory access. In this paper, we present SpecEE, a fast LLM inference
engine with speculative early exiting. (1) At the algorithm level, we propose
the speculation-based lightweight predictor design by exploiting the
probabilistic correlation between the speculative tokens and the correct
results and high parallelism of GPUs. (2) At the system level, we point out
that not all layers need a predictor and design the two-level heuristic
predictor scheduling engine based on skewed distribution and contextual
similarity. (3) At the mapping level, we point out that different decoding
methods share the same essential characteristics, and propose the context-aware
merged mapping for predictor with efficient GPU implementations to support
speculative decoding, and form a framework for various existing orthogonal
acceleration techniques (e.g., quantization and sparse activation) on cloud and
personal computer (PC) scenarios, successfully pushing the Pareto frontier of
accuracy and speedup. It is worth noting that SpecEE can be applied to any LLM
by negligible training overhead in advance without affecting the model original
parameters. Extensive experiments show that SpecEE achieves 2.25x and 2.43x
speedup with Llama2-7B on cloud and PC scenarios respectively.
