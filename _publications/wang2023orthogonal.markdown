---
layout: publication
title: 'Orthogonal Subspace Learning For Language Model Continual Learning'
authors: Wang Xiao, Chen Tianze, Ge Qiming, Xia Han, Bao Rong, Zheng Rui, Zhang Qi, Gui Tao, Huang Xuanjing
conference: "Arxiv"
year: 2023
bibkey: wang2023orthogonal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14152"}
tags: ['Fine Tuning', 'RAG', 'Reinforcement Learning']
---
Benefiting from massive corpora and advanced hardware large language models (LLMs) exhibit remarkable capabilities in language understanding and generation. However their performance degrades in scenarios where multiple tasks are encountered sequentially also known as catastrophic forgetting. In this paper we propose orthogonal low-rank adaptation (O-LoRA) a simple and efficient approach for continual learning in language models effectively mitigating catastrophic forgetting while learning new tasks. Specifically O-LoRA learns tasks in different (low-rank) vector subspaces that are kept orthogonal to each other in order to minimize interference. Our method induces only marginal additional parameter costs and requires no user data storage for replay. Experimental results on continual learning benchmarks show that our method outperforms state-of-the-art methods. Furthermore compared to previous approaches our method excels in preserving the generalization ability of LLMs on unseen tasks.
