---
layout: publication
title: 'Resolving Task Objective Conflicts In Unified Multimodal Understanding And Generation Via Task-aware Mixture-of-experts'
authors: Jiaxing Zhang, Xinyi Zeng, Hao Tang
conference: "Arxiv"
year: 2025
bibkey: zhang2025resolving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03591'}
tags: ['Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Multimodal Models', 'Pretraining Methods']
---
Unified multimodal large language models (MLLMs) based on end-to-end autoregressive (AR) transformers effectively integrate both understanding and generation tasks within a single framework. However, intrinsic Task Objective Conflicts between high-level semantic abstraction in understanding and fine-grained detail preservation in generation pose significant challenges, often leading to suboptimal trade-offs and task interference. Existing solutions, such as decoupling shared visual encoders, fall short of fundamentally resolving these conflicts due to inherent AR architecture. In this paper, we propose a novel approach that decouples internal components of AR to resolve task objective conflicts. Specifically, we design UTAMoE, a Unified Task-Aware Mixture-of-Experts (MoE) framework that decouples internal AR modules via a Task-Aware MoE Layer to create task-specific optimization subpaths. To enhance task differentiation while maintaining overall coordination, we introduce a novel Two-Stage Training Strategy. Extensive experiments on multimodal benchmarks demonstrate that UTAMoE mitigates task objective conflicts, achieving state-of-the-art performance across various tasks. Visualizations and ablation studies further validate the effectiveness of our approach.
