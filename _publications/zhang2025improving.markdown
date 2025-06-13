---
layout: publication
title: 'STAIR: Improving Safety Alignment With Introspective Reasoning'
authors: Yichi Zhang, Siyuan Zhang, Yao Huang, Zeyu Xia, Zhengwei Fang, Xiao Yang, Ranjie Duan, Dong Yan, Yinpeng Dong, Jun Zhu
conference: "Arxiv"
year: 2025
bibkey: zhang2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02384"}
  - {name: "Code", url: "https://github.com/thu-ml/STAIR"}
tags: ['Responsible AI', 'Security', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Has Code', 'Applications']
---
Ensuring the safety and harmlessness of Large Language Models (LLMs) has
become equally critical as their performance in applications. However, existing
safety alignment methods typically suffer from safety-performance trade-offs
and the susceptibility to jailbreak attacks, primarily due to their reliance on
direct refusals for malicious queries. In this paper, we propose STAIR, a novel
framework that integrates SafeTy Alignment with Itrospective Reasoning. We
enable LLMs to identify safety risks through step-by-step analysis by
self-improving chain-of-thought (CoT) reasoning with safety awareness. STAIR
first equips the model with a structured reasoning capability and then advances
safety alignment via iterative preference optimization on step-level reasoning
data generated using our newly proposed Safety-Informed Monte Carlo Tree Search
(SI-MCTS). We further train a process reward model on this data to guide
test-time searches for improved responses. Extensive experiments show that
STAIR effectively mitigates harmful outputs while better preserving
helpfulness, compared to instinctive alignment strategies. With test-time
scaling, STAIR achieves a safety performance comparable to Claude-3.5 against
popular jailbreak attacks. Relevant resources in this work are available at
https://github.com/thu-ml/STAIR.
