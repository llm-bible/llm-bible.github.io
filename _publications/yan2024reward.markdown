---
layout: publication
title: 'Reward-robust RLHF In Llms'
authors: Yuzi Yan, Xingzhou Lou, Jialian Li, Yiping Zhang, Jian Xie, Chao Yu, Yu Wang, Dong Yan, Yuan Shen
conference: "Arxiv"
year: 2024
bibkey: yan2024reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15360"}
tags: ['Agentic', 'Security', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Merging']
---
As Large Language Models (LLMs) continue to progress toward more advanced
forms of intelligence, Reinforcement Learning from Human Feedback (RLHF) is
increasingly seen as a key pathway toward achieving Artificial General
Intelligence (AGI). However, the reliance on reward-model-based (RM-based)
alignment methods introduces significant challenges due to the inherent
instability and imperfections of Reward Models (RMs), which can lead to
critical issues such as reward hacking and misalignment with human intentions.
In this paper, we introduce a reward-robust RLHF framework aimed at addressing
these fundamental challenges, paving the way for more reliable and resilient
learning in LLMs. Our approach introduces a novel optimization objective that
carefully balances performance and robustness by incorporating Bayesian Reward
Model Ensembles (BRME) to model the uncertainty set of reward functions. This
allows the framework to integrate both nominal performance and minimum reward
signals, ensuring more stable learning even with imperfect RMs. Empirical
results demonstrate that our framework consistently outperforms baselines
across diverse benchmarks, showing improved accuracy and long-term stability.
We also provide a theoretical analysis, demonstrating that reward-robust RLHF
approaches the stability of constant reward settings, which proves to be
acceptable even in a stochastic-case analysis. Together, these contributions
highlight the framework potential to enhance both the performance and stability
of LLM alignment.
