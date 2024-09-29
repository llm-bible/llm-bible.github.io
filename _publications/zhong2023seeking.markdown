---
layout: publication
title: Seeking Neural Nuggets: Knowledge Transfer In Large Language Models From A Parametric Perspective
authors: Zhong Ming, An Chenxin, Chen Weizhu, Han Jiawei, He Pengcheng
conference: "Arxiv"
year: 2023
bibkey: zhong2023seeking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11451"}
  - {name: "Code", url: "https://maszhongming.github.io/ParaKnowTransfer"}
tags: ['Fine Tuning', 'Has Code', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) inherently encode a wealth of knowledge within their parameters through pre-training on extensive corpora. While prior research has delved into operations on these parameters to manipulate the underlying implicit knowledge (encompassing detection editing and merging) there remains an ambiguous understanding regarding their transferability across models with varying scales. In this paper we seek to empirically investigate knowledge transfer from larger to smaller models through a parametric perspective. To achieve this we employ sensitivity-based techniques to extract and align knowledge-specific parameters between different LLMs. Moreover the LoRA module is used as the intermediary mechanism for injecting the extracted knowledge into smaller models. Evaluations across four benchmarks validate the efficacy of our proposed method. Our findings highlight the critical factors contributing to the process of parametric knowledge transfer underscoring the transferability of model parameters across LLMs of different scales. Project website https://maszhongming.github.io/ParaKnowTransfer."
