---
layout: publication
title: EE45;LLM Large45;scale Training And Inference Of Early45;exit Large Language Models With 3D Parallelism
authors: Chen Yanxi, Pan Xuchen, Li Yaliang, Ding Bolin, Zhou Jingren
conference: "Arxiv"
year: 2023
bibkey: chen2023ee
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04916"}
  - {name: "Code", url: "https://github.com/pan&#45;x&#45;c/EE&#45;LLM"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We present EE45;LLM a framework for large45;scale training and inference of early45;exit large language models (LLMs). While recent works have shown preliminary evidence for the efficacy of early exiting in accelerating LLM inference EE45;LLM makes a foundational step towards scaling up early45;exit LLMs by supporting their training and inference with massive 3D parallelism. Built upon Megatron45;LM EE45;LLM implements a variety of algorithmic innovations and performance optimizations tailored to early exiting including a lightweight method that facilitates backpropagation for the early45;exit training objective with pipeline parallelism techniques of leveraging idle resources in the original pipeline schedule for computation related to early45;exit layers and two approaches of early45;exit inference that are compatible with KV caching for autoregressive generation. Our analytical and empirical study shows that EE45;LLM achieves great training efficiency with negligible computational overhead compared to standard LLM training as well as outstanding inference speedup without compromising output quality. To facilitate further research and adoption we release EE45;LLM at https://github.com/pan&#45;x&#45;c/EE&#45;LLM.
