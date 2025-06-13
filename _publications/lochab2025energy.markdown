---
layout: publication
title: 'Energy-based Reward Models For Robust Language Model Alignment'
authors: Anamika Lochab, Ruqi Zhang
conference: "Arxiv"
year: 2025
bibkey: lochab2025energy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13134"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Reward models (RMs) are essential for aligning Large Language Models (LLMs)
with human preferences. However, they often struggle with capturing complex
human preferences and generalizing to unseen data. To address these challenges,
we introduce Energy-Based Reward Model (EBRM), a lightweight post-hoc
refinement framework that enhances RM robustness and generalization. EBRM
models the reward distribution explicitly, capturing uncertainty in human
preferences and mitigating the impact of noisy or misaligned annotations. It
achieves this through conflict-aware data filtering, label-noise-aware
contrastive training, and hybrid initialization. Notably, EBRM enhances RMs
without retraining, making it computationally efficient and adaptable across
different models and tasks. Empirical evaluations on RM benchmarks demonstrate
significant improvements in both robustness and generalization, achieving up to
a 5.97% improvement in safety-critical alignment tasks compared to standard
RMs. Furthermore, reinforcement learning experiments confirm that our refined
rewards enhance alignment quality, effectively delaying reward hacking. These
results demonstrate our approach as a scalable and effective enhancement for
existing RMs and alignment pipelines. The code is available at EBRM.
