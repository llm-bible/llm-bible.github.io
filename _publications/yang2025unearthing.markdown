---
layout: publication
title: 'Unearthing Gems From Stones: Policy Optimization With Negative Sample Augmentation For LLM Reasoning'
authors: Zhaohui Yang, Shilei Jiang, Chen Hu, Linjing Li, Shihong Deng, Daxin Jiang
conference: "Arxiv"
year: 2025
bibkey: yang2025unearthing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14403'}
tags: ['RAG', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Recent advances in reasoning language models have witnessed a paradigm shift from short to long CoT pattern. Given the substantial computational cost of rollouts in long CoT models, maximizing the utility of fixed training datasets becomes crucial. Our analysis reveals that negative responses contain valuable components such as self-reflection and error-correction steps, yet primary existing methods either completely discard negative samples (RFT) or apply equal penalization across all tokens (RL), failing to leverage these potential learning signals. In light of this, we propose Behavior Constrained Policy Gradient with Negative Sample Augmentation (BCPG-NSA), a fine-grained offline RL framework that encompasses three stages: 1) sample segmentation, 2) consensus-based step correctness assessment combining LLM and PRM judgers, and 3) policy optimization with NSA designed to effectively mine positive steps within negative samples. Experimental results show that BCPG-NSA outperforms baselines on several challenging math/coding reasoning benchmarks using the same training dataset, achieving improved sample efficiency and demonstrating robustness and scalability when extended to multiple iterations.
