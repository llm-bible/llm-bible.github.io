---
layout: publication
title: 'Learning To Reason Without External Rewards'
authors: Xuandong Zhao, Zhewei Kang, Aosong Feng, Sergey Levine, Dawn Song
conference: "Arxiv"
year: 2025
bibkey: zhao2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19590'}
  - {name: "Code", url: 'https://github.com/sunblaze-ucb/Intuitor'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
Training large language models (LLMs) for complex reasoning via Reinforcement Learning with Verifiable Rewards (RLVR) is effective but limited by reliance on costly, domain-specific supervision. We explore Reinforcement Learning from Internal Feedback (RLIF), a framework that enables LLMs to learn from intrinsic signals without external rewards or labeled data. We propose Intuitor, an RLIF method that uses a model's own confidence, termed self-certainty, as its sole reward signal. Intuitor replaces external rewards in Group Relative Policy Optimization (GRPO) with self-certainty scores, enabling fully unsupervised learning. Experiments demonstrate that Intuitor matches GRPO's performance on mathematical benchmarks while achieving superior generalization to out-of-domain tasks like code generation, without requiring gold solutions or test cases. Our findings show that intrinsic model signals can drive effective learning across domains, offering a scalable alternative to RLVR for autonomous AI systems where verifiable rewards are unavailable. Code is available at https://github.com/sunblaze-ucb/Intuitor
