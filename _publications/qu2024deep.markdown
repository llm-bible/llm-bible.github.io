---
layout: publication
title: DEEP-ICL Definition-enriched Experts For Language Model In-context Learning
authors: Qu Xingwei, Liang Yiming, Wang Yucheng, Zheng Tianyu, Yue Tommy, Ma Lei, Huang Stephen W., Zhang Jiajun, Shi Yinan, Lin Chenghua, Fu Jie, Zhang Ge
conference: "Arxiv"
year: 2024
bibkey: qu2024deep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04233"}
tags: ['Few Shot', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
It has long been assumed that the sheer number of parameters in large language models (LLMs) drives in-context learning (ICL) capabilities enabling remarkable performance improvements by leveraging task-specific demonstrations. Challenging this hypothesis we introduce DEEP-ICL a novel task Definition Enriched ExPert Ensembling methodology for ICL. DEEP-ICL explicitly extracts task definitions from given demonstrations and generates responses through learning task-specific examples. We argue that improvement from ICL does not directly rely on model size but essentially stems from understanding task definitions and task-guided learning. Inspired by this DEEP-ICL combines two 3B models with distinct roles (one for concluding task definitions and the other for learning task demonstrations) and achieves comparable performance to LLaMA2-13B. Furthermore our framework outperforms conventional ICL by overcoming pretraining sequence length limitations by supporting unlimited demonstrations. We contend that DEEP-ICL presents a novel alternative for achieving efficient few-shot learning extending beyond the conventional ICL.
