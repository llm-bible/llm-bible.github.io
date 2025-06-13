---
layout: publication
title: 'System-1.5 Reasoning: Traversal In Language And Latent Spaces With Dynamic Shortcuts'
authors: Xiaoqiang Wang, Suyuchen Wang, Yun Zhu, Bang Liu
conference: "Arxiv"
year: 2025
bibkey: wang2025system
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18962'}
tags: ['Transformer', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Tools', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Chain-of-thought (CoT) reasoning enables large language models (LLMs) to move beyond fast System-1 responses and engage in deliberative System-2 reasoning. However, this comes at the cost of significant inefficiency due to verbose intermediate output. Recent latent-space reasoning methods improve efficiency by operating on hidden states without decoding into language, yet they treat all steps uniformly, failing to distinguish critical deductions from auxiliary steps and resulting in suboptimal use of computational resources. In this paper, we propose System-1.5 Reasoning, an adaptive reasoning framework that dynamically allocates computation across reasoning steps through shortcut paths in latent space. Specifically, System-1.5 Reasoning introduces two types of dynamic shortcuts. The model depth shortcut (DS) adaptively reasons along the vertical depth by early exiting non-critical tokens through lightweight adapter branches, while allowing critical tokens to continue through deeper Transformer layers. The step shortcut (SS) reuses hidden states across the decoding steps to skip trivial steps and reason horizontally in latent space. Training System-1.5 Reasoning involves a two-stage self-distillation process: first distilling natural language CoT into latent-space continuous thought, and then distilling full-path System-2 latent reasoning into adaptive shortcut paths (System-1.5 Reasoning). Experiments on reasoning tasks demonstrate the superior performance of our method. For example, on GSM8K, System-1.5 Reasoning achieves reasoning performance comparable to traditional CoT fine-tuning methods while accelerating inference by over 20x and reducing token generation by 92.31% on average.
