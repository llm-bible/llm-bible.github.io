---
layout: publication
title: 'Harnessing Your DRAM And SSD For Sustainable And Accessible LLM Inference With Mixed-precision And Multi-level Caching'
authors: Jie Peng, Zhang Cao, Huaizhi Qu, Zhengyu Zhang, Chang Guo, Yanyong Zhang, Zhichao Cao, Tianlong Chen
conference: "Arxiv"
year: 2024
bibkey: peng2024harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14740"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Quantization', 'Applications']
---
Although Large Language Models (LLMs) have demonstrated remarkable
capabilities, their massive parameter counts and associated extensive computing
make LLMs' deployment the main part of carbon emission from nowadays AI
applications. Compared to modern GPUs like H\\(100\\), it would be significantly
carbon-sustainable if we could leverage old-fashioned GPUs such as M\\(40\\) (as
shown in Figure 1, M\\(40\\) only has one third carbon emission of H\\(100\\)'s) for
LLM servings. However, the limited High Bandwidth Memory (HBM) available on
such GPU often cannot support the loading of LLMs due to the gigantic model
size and intermediate activation data, making their serving challenging. For
instance, a LLaMA2 model with \\(70\\)B parameters typically requires \\(128\\)GB for
inference, which substantially surpasses \\(24\\)GB HBM in a \\(3090\\) GPU and remains
infeasible even considering the additional \\(64\\)GB DRAM. To address this
challenge, this paper proposes a mixed-precision with a model modularization
algorithm to enable LLM inference on outdated hardware with resource
constraints. (The precision denotes the numerical precision like FP16, INT8,
INT4) and multi-level caching (M2Cache).)
  Specifically, our M2Cache first modulizes neurons in LLM and creates their
importance ranking. Then, it adopts a dynamic sparse mixed-precision
quantization mechanism in weight space to reduce computational demands and
communication overhead at each decoding step. It collectively lowers the
operational carbon emissions associated with LLM inference. Moreover, M2Cache
introduces a three-level cache management system with HBM, DRAM, and SSDs that
complements the dynamic sparse mixed-precision inference. To enhance
communication efficiency, M2Cache maintains a neuron-level mixed-precision LRU
cache in HBM, a larger layer-aware cache in DRAM, and a full model in SSD.
