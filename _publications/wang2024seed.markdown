---
layout: publication
title: SEED Accelerating Reasoning Tree Construction Via Scheduled Speculative Decoding
authors: Wang Zhenglin, Wu Jialong, Lai Yilong, Zhang Congzhi, Zhou Deyu
conference: "Arxiv"
year: 2024
bibkey: wang2024seed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18200"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) demonstrate remarkable emergent abilities across various tasks yet fall short of complex reasoning and planning tasks. The tree-search-based reasoning methods address this by surpassing the capabilities of chain-of-thought prompting encouraging exploration of intermediate steps. However such methods introduce significant inference latency due to the systematic exploration and evaluation of multiple thought paths. This paper introduces SeeD a novel and efficient inference framework to optimize runtime speed and GPU memory management concurrently. By employing a scheduled speculative execution SeeD efficiently handles multiple iterations for the thought generation and the state evaluation leveraging a rounds-scheduled strategy to manage draft model dispatching. Extensive experimental evaluations on three reasoning datasets demonstrate superior speedup performance of SeeD providing a viable path for batched inference in training-free speculative decoding.
