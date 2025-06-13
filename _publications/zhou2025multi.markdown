---
layout: publication
title: 'Debate, Reflect, And Distill: Multi-agent Feedback With Tree-structured Preference Optimization For Efficient Language Model Enhancement'
authors: Xiaofeng Zhou, Heyan Huang, Lizi Liao
conference: "Arxiv"
year: 2025
bibkey: zhou2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03541"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation']
---
Large Language Models (LLMs) continue to set new standards in knowledge-intensive and complex reasoning tasks, yet their high computational demands limit widespread adoption. While distilling large models into smaller ones offers a sustainable solution, current techniques--such as static knowledge distillation, resource-intensive reinforcement learning from human feedback, or limited self-reflection--struggle to yield substantial and lasting performance gains. In this paper, we present a novel Debate and Reflect (D&R) framework that orchestrates multi-turn debates between smaller models and stronger teacher models, eliciting actionable feedback (e.g., error analysis, corrective strategies) to guide student models. Further, we introduce Tree-structured Direct Preference Optimization (T-DPO) to efficiently leverage these debate logs, organizing interactions into a hierarchical format for effective training. Empirical evaluations across diverse NLP benchmarks demonstrate that our approach significantly improves smaller-model accuracy, robustness, and generalization, outperforming conventional baselines by a large margin.
