---
layout: publication
title: 'Personalized Soups: Personalized Large Language Model Alignment Via Post-hoc Parameter Merging'
authors: Jang Joel, Kim Seungone, Lin Bill Yuchen, Wang Yizhong, Hessel Jack, Zettlemoyer Luke, Hajishirzi Hannaneh, Choi Yejin, Ammanabrolu Prithviraj
conference: "Arxiv"
year: 2023
bibkey: jang2023personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11564"}
  - {name: "Code", url: "https://github.com/joeljang/RLPHF"}
tags: ['Agentic', 'Has Code', 'Merging', 'Reinforcement Learning']
---
"While Reinforcement Learning from Human Feedback (RLHF) aligns Large Language Models (LLMs) with general, aggregate human preferences, it is suboptimal for learning diverse, individual perspectives. In this work, we study Reinforcement Learning from Personalized Human Feedback (RLPHF) problem, wherein LLMs are aligned to multiple (sometimes conflicting) preferences by modeling alignment as a Multi-Objective Reinforcement Learning (MORL) problem. Compared to strong single-objective baselines, we show that we can achieve personalized alignment by decomposing preferences into multiple dimensions. These dimensions are defined based on personalizations that are declared as desirable by the user. In this work, we show that they can be efficiently trained independently in a distributed manner and combined effectively post-hoc through parameter merging. The code is available at https://github.com/joeljang/RLPHF."
