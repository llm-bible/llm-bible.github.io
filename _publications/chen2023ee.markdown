---
layout: publication
title: 'EE-LLM: Large-scale Training And Inference Of Early-exit Large Language Models With 3D Parallelism'
authors: Chen Yanxi, Pan Xuchen, Li Yaliang, Ding Bolin, Zhou Jingren
conference: "Arxiv"
year: 2023
bibkey: chen2023ee
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04916"}
  - {name: "Code", url: "https://github.com/pan-x-c/EE-LLM"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Large Scale Training', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We present EE-LLM, a framework for large-scale training and inference of
early-exit large language models (LLMs). While recent works have shown
preliminary evidence for the efficacy of early exiting in accelerating LLM
inference, EE-LLM makes a foundational step towards scaling up early-exit LLMs
by supporting their training and inference with massive 3D parallelism. Built
upon Megatron-LM, EE-LLM implements a variety of algorithmic innovations and
performance optimizations tailored to early exiting, including a lightweight
method that facilitates backpropagation for the early-exit training objective
with pipeline parallelism, techniques of leveraging idle resources in the
original pipeline schedule for computation related to early-exit layers, and
two approaches of early-exit inference that are compatible with KV caching for
autoregressive generation. Our analytical and empirical study shows that EE-LLM
achieves great training efficiency with negligible computational overhead
compared to standard LLM training, as well as outstanding inference speedup
without compromising output quality. To facilitate further research and
adoption, we release EE-LLM at https://github.com/pan-x-c/EE-LLM.
