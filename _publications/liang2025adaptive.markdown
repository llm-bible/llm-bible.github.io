---
layout: publication
title: 'Adaptive Helpfulness-harmlessness Alignment With Preference Vectors'
authors: Ren-wei Liang, Chin-ting Hsu, Chan-hung Yu, Saransh Agrawal, Shih-cheng Huang, Shang-tse Chen, Kuan-hao Huang, Shao-hua Sun
conference: "Arxiv"
year: 2025
bibkey: liang2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20106"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques']
---
Ensuring that large language models (LLMs) are both helpful and harmless is a
critical challenge, as overly strict constraints can lead to excessive
refusals, while permissive models risk generating harmful content. Existing
approaches, such as reinforcement learning from human feedback (RLHF) and
direct preference optimization (DPO), attempt to balance these trade-offs but
suffer from performance conflicts, limited controllability, and poor
extendability. To address these issues, we propose Preference Vector, a novel
framework inspired by task arithmetic. Instead of optimizing multiple
preferences within a single objective, we train separate models on individual
preferences, extract behavior shifts as preference vectors, and dynamically
merge them at test time. This modular approach enables fine-grained,
user-controllable preference adjustments and facilitates seamless integration
of new preferences without retraining. Experiments show that our proposed
Preference Vector framework improves helpfulness without excessive
conservatism, allows smooth control over preference trade-offs, and supports
scalable multi-preference alignment.
