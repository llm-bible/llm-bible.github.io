---
layout: publication
title: 'Unconstrained Model Merging For Enhanced LLM Reasoning'
authors: Yiming Zhang, Baoyi He, Shengyu Zhang, Yuhao Fu, Qi Zhou, Zhijie Sang, Zijin Hong, Kejing Yang, Wenjun Wang, Jianbo Yuan, Guanghan Ning, Linyi Li, Chunlin Ji, Fei Wu, Hongxia Yang
conference: "Arxiv"
year: 2024
bibkey: zhang2024unconstrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13699"}
tags: ['Fine-Tuning', 'Tools', 'Model Architecture', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
Recent advancements in building domain-specific large language models (LLMs)
have shown remarkable success, especially in tasks requiring reasoning
abilities like logical inference over complex relationships and multi-step
problem solving. However, creating a powerful all-in-one LLM remains
challenging due to the need for proprietary data and vast computational
resources. As a resource-friendly alternative, we explore the potential of
merging multiple expert models into a single LLM. Existing studies on model
merging mainly focus on generalist LLMs instead of domain experts, or the LLMs
under the same architecture and size. In this work, we propose an unconstrained
model merging framework that accommodates both homogeneous and heterogeneous
model architectures with a focus on reasoning tasks. A fine-grained layer-wise
weight merging strategy is designed for homogeneous models merging, while
heterogeneous model merging is built upon the probabilistic distribution
knowledge derived from instruction-response fine-tuning data. Across 7
benchmarks and 9 reasoning-optimized LLMs, we reveal key findings that
combinatorial reasoning emerges from merging which surpasses simple additive
effects. We propose that unconstrained model merging could serve as a
foundation for decentralized LLMs, marking a notable progression from the
existing centralized LLM framework. This evolution could enhance wider
participation and stimulate additional advancement in the field of artificial
intelligence, effectively addressing the constraints posed by centralized
models.
