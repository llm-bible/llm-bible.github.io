---
layout: publication
title: 'Infigfusion: Graph-on-logits Distillation Via Efficient Gromov-wasserstein For Model Fusion'
authors: Yuanyi Wang, Zhaoyi Yan, Yiming Zhang, Qi Zhou, Yanggan Gu, Fei Wu, Hongxia Yang
conference: "Arxiv"
year: 2025
bibkey: wang2025graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13893"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Merging', 'Distillation']
---
Recent advances in large language models (LLMs) have intensified efforts to fuse heterogeneous open-source models into a unified system that inherits their complementary strengths. Existing logit-based fusion methods maintain inference efficiency but treat vocabulary dimensions independently, overlooking semantic dependencies encoded by cross-dimension interactions. These dependencies reflect how token types interact under a model's internal reasoning and are essential for aligning models with diverse generation behaviors. To explicitly model these dependencies, we propose \textbf\{InfiGFusion\}, the first structure-aware fusion framework with a novel \textit\{Graph-on-Logits Distillation\} (GLD) loss. Specifically, we retain the top-\\(k\\) logits per output and aggregate their outer products across sequence positions to form a global co-activation graph, where nodes represent vocabulary channels and edges quantify their joint activations. To ensure scalability and efficiency, we design a sorting-based closed-form approximation that reduces the original \\(O(n^4)\\) cost of Gromov-Wasserstein distance to \\(O(n log n)\\), with provable approximation guarantees. Experiments across multiple fusion settings show that GLD consistently improves fusion quality and stability. InfiGFusion outperforms SOTA models and fusion baselines across 11 benchmarks spanning reasoning, coding, and mathematics. It shows particular strength in complex reasoning tasks, with +35.6 improvement on Multistep Arithmetic and +37.06 on Causal Judgement over SFT, demonstrating superior multi-step and relational inference.
