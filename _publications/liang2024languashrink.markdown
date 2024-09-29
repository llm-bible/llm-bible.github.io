---
layout: publication
title: Languashrink Reducing Token Overhead With Psycholinguistics
authors: Liang Xuechen, Tao Meiling, Xia Yinghui, Shi Tianyu, Wang Jun, Yang Jingsong
conference: "Arxiv"
year: 2024
bibkey: liang2024languashrink
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00855"}
tags: ['Agentic', 'Distillation', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
As large language models (LLMs) improve their capabilities in handling complex tasks the issues of computational cost and efficiency due to long prompts are becoming increasingly prominent. To accelerate model inference and reduce costs we propose an innovative prompt compression framework called LanguaShrink. Inspired by the observation that LLM performance depends on the density and position of key information in the input prompts LanguaShrink leverages psycholinguistic principles and the Ebbinghaus memory curve to achieve task-agnostic prompt compression. This effectively reduces prompt length while preserving essential information. We referred to the training method of OpenChat.The framework introduces part-of-speech priority compression and data distillation techniques using smaller models to learn compression targets and employing a KL-regularized reinforcement learning strategy for training. Additionally we adopt a chunk-based compression algorithm to achieve adjustable compression rates. We evaluate our method on multiple datasets including LongBench ZeroScrolls Arxiv Articles and a newly constructed novel test set. Experimental results show that LanguaShrink maintains semantic similarity while achieving up to 26 times compression. Compared to existing prompt compression methods LanguaShrink improves end-to-end latency by 1.43 times.
