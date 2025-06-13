---
layout: publication
title: 'Self-critique Guided Iterative Reasoning For Multi-hop Question Answering'
authors: Zheng Chu, Huiming Fan, Jingchang Chen, Qianyu Wang, Mingda Yang, Jiafeng Liang, Zhongjie Wang, Hao Li, Guo Tang, Ming Liu, Bing Qin
conference: "Arxiv"
year: 2025
bibkey: chu2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19112'}
  - {name: "Code", url: 'https://github.com/zchuz/SiGIR-MHQA'}
tags: ['Has Code', 'Applications', 'Training Techniques', 'SIGIR', 'Fine-Tuning']
---
Although large language models (LLMs) have demonstrated remarkable reasoning capabilities, they still face challenges in knowledge-intensive multi-hop reasoning. Recent work explores iterative retrieval to address complex problems. However, the lack of intermediate guidance often results in inaccurate retrieval and flawed intermediate reasoning, leading to incorrect reasoning. To address these, we propose Self-Critique Guided Iterative Reasoning (SiGIR), which uses self-critique feedback to guide the iterative reasoning process. Specifically, through end-to-end training, we enable the model to iteratively address complex problems via question decomposition. Additionally, the model is able to self-evaluate its intermediate reasoning steps. During iterative reasoning, the model engages in branching exploration and employs self-evaluation to guide the selection of promising reasoning trajectories. Extensive experiments on three multi-hop reasoning datasets demonstrate the effectiveness of our proposed method, surpassing the previous SOTA by \\(8.6%\\). Furthermore, our thorough analysis offers insights for future research. Our code, data, and models are available at Github: https://github.com/zchuz/SiGIR-MHQA.
