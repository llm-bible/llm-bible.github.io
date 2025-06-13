---
layout: publication
title: 'Reinforced Lifelong Editing For Language Models'
authors: Zherui Li, Houcheng Jiang, Hao Chen, Baolong Bi, Zhenhong Zhou, Fei Sun, Junfeng Fang, Xiang Wang
conference: "Arxiv"
year: 2025
bibkey: li2025reinforced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05759"}
  - {name: "Code", url: "https://github.com/zhrli324/RLEdit"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Has Code', 'Pre-Training']
---
Large language models (LLMs) acquire information from pre-training corpora,
but their stored knowledge can become inaccurate or outdated over time. Model
editing addresses this challenge by modifying model parameters without
retraining, and prevalent approaches leverage hypernetworks to generate these
parameter updates. However, they face significant challenges in lifelong
editing due to their incompatibility with LLM parameters that dynamically
change during the editing process. To address this, we observed that
hypernetwork-based lifelong editing aligns with reinforcement learning modeling
and proposed RLEdit, an RL-based editing method. By treating editing losses as
rewards and optimizing hypernetwork parameters at the full knowledge sequence
level, we enable it to precisely capture LLM changes and generate appropriate
parameter updates. Our extensive empirical evaluation across several LLMs
demonstrates that RLEdit outperforms existing methods in lifelong editing with
superior effectiveness and efficiency, achieving a 59.24% improvement while
requiring only 2.11% of the time compared to most approaches. Our code is
available at: https://github.com/zhrli324/RLEdit.
