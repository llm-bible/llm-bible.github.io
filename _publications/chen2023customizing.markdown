---
layout: publication
title: Confidant: Customizing Transformer-based Llms Via Collaborative Edge Training
authors: Chen Yuhao, Yan Yuxuan, Yang Qianqian, Shu Yuanchao, He Shibo, Chen Jiming
conference: "Arxiv"
year: 2023
bibkey: chen2023customizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13381"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer-based large language models (LLMs) have demonstrated impressive capabilities in a variety of natural language processing (NLP) tasks. Nonetheless it is challenging to deploy and fine-tune LLMs on mobile edge devices with limited computing memory and energy budgets. In this paper we propose Confidant a multi-backend collaborative training framework for customizing state-of-the-art LLMs on commodity mobile devices like smartphones. Confidant partitions an LLM into several sub-models so that each fits into a mobile devices memory. A pipeline parallel training mechanism is further developed to ensure fast and efficient distributed training. In addition we propose a novel backend scheduler to allocate different attention heads to heterogeneous compute hardware including mobile CPU and GPUs to maximize the compute resource utilization on each edge device. Our preliminary experimental results show that Confidant achieves at most 45.337; memory reduction and 8.03x inference speedup in practical settings.
