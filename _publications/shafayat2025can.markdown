---
layout: publication
title: 'Can Large Reasoning Models Self-train?'
authors: Sheikh Shafayat, Fahim Tajwar, Ruslan Salakhutdinov, Jeff Schneider, Andrea Zanette
conference: "Arxiv"
year: 2025
bibkey: shafayat2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21444"}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Reinforcement Learning']
---
Scaling the performance of large language models (LLMs) increasingly depends on methods that reduce reliance on human supervision. Reinforcement learning from automated verification offers an alternative, but it incurs scalability limitations due to dependency upon human-designed verifiers. Self-training, where the model's own judgment provides the supervisory signal, presents a compelling direction. We propose an online self-training reinforcement learning algorithm that leverages the model's self-consistency to infer correctness signals and train without any ground-truth supervision. We apply the algorithm to challenging mathematical reasoning tasks and show that it quickly reaches performance levels rivaling reinforcement-learning methods trained explicitly on gold-standard answers. Additionally, we analyze inherent limitations of the algorithm, highlighting how the self-generated proxy reward initially correlated with correctness can incentivize reward hacking, where confidently incorrect outputs are favored. Our results illustrate how self-supervised improvement can achieve significant performance gains without external labels, while also revealing its fundamental challenges.
