---
layout: publication
title: 'Two Is Better Than One: Rotations Scale Loras'
authors: Hongcan Guo, Guoshun Nan, Yuan Yang, Diyang Zhang, Haotian Li, Zhican Chen, Qinchuan Zhou, Yuhan Ran, Xinye Cao, Sicong Leng, Xiaofeng Tao, Xudong Jiang
conference: "Arxiv"
year: 2025
bibkey: guo2025two
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23184'}
tags: ['Reinforcement Learning', 'RAG', 'Fine-Tuning']
---
Scaling Low-Rank Adaptation (LoRA)-based Mixture-of-Experts (MoE) facilitates large language models (LLMs) to efficiently adapt to diverse tasks. However, traditional gating mechanisms that route inputs to the best experts may fundamentally hinder LLMs' scalability, leading to poor generalization and underfitting issues. We identify that the root cause lies in the restricted expressiveness of existing weighted-sum mechanisms, both within and outside the convex cone of LoRA representations. This motivates us to propose RadarGate, a novel geometrically inspired gating method that introduces rotational operations of LoRAs representations to boost the expressiveness and facilitate richer feature interactions among multiple LoRAs for scalable LLMs. Specifically, we first fuse each LoRA representation to other LoRAs using a learnable component and then feed the output to a rotation matrix. This matrix involves learnable parameters that define the relative angular relationship between LoRA representations. Such a simple yet effective mechanism provides an extra degree of freedom, facilitating the learning of cross-LoRA synergies and properly tracking the challenging poor generalization and underfitting issues as the number of LoRA grows. Extensive experiments on 6 public benchmarks across 21 tasks show the effectiveness of our RadarGate for scaling LoRAs. We also provide valuable insights, revealing that the rotations to each pair of representations are contrastive, encouraging closer alignment of semantically similar representations during geometrical transformation while pushing distance ones further apart. We will release our code to the community.
