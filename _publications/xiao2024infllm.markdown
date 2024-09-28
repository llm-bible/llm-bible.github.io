---
layout: publication
title: InfLLM Training-Free Long-Context Extrapolation for LLMs with an Efficient Context Memory
authors: Xiao Chaojun, Zhang Pengle, Han Xu, Xiao Guangxuan, Lin Yankai, Zhang Zhengyan, Liu Zhiyuan, Sun Maosong
conference: "Arxiv"
year: 2024
bibkey: xiao2024infllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04617"}
  - {name: "Code", url: "https://github.com/thunlp/InfLLM"}
tags: ['ARXIV', 'Agentic', 'Applications', 'Attention Mechanism', 'Fine Tuning', 'Has Code', 'LLM', 'NLP', 'Pretraining Methods', 'Reinforcement Learning']
---
Large language models (LLMs) have emerged as a cornerstone in real-world applications with lengthy streaming inputs (e.g. LLM-driven agents). However existing LLMs pre-trained on sequences with a restricted maximum length cannot process longer sequences due to the out-of-domain and distraction issues. Common solutions often involve continual pre-training on longer sequences which will introduce expensive computational overhead and uncontrollable change in model capabilities. In this paper we unveil the intrinsic capacity of LLMs for understanding extremely long sequences without any fine-tuning. To this end we introduce a training-free memory-based method InfLLM. Specifically InfLLM stores distant contexts into additional memory units and employs an efficient mechanism to lookup token-relevant units for attention computation. Thereby InfLLM allows LLMs to efficiently process long sequences with a limited context window and well capture long-distance dependencies. Without any training InfLLM enables LLMs that are pre-trained on sequences consisting of a few thousand tokens to achieve comparable performance with competitive baselines that continually train these LLMs on long sequences. Even when the sequence length is scaled to 1024K InfLLM still effectively captures long-distance dependencies. Our code can be found in url https://github.com/thunlp/InfLLM.
