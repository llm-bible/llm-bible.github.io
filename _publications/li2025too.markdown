---
layout: publication
title: 'TL;DR: Too Long, Do Re-weighting For Effcient LLM Reasoning Compression'
authors: Zhong-zhi Li, Xiao Liang, Zihao Tang, Lei Ji, Peijie Wang, Haotian Xu, Xing W, Haizhen Huang, Weiwei Deng, Ying Nian Wu, Yeyun Gong, Zhijiang Guo, Xiao Liu, Fei Yin, Cheng-lin Liu
conference: "Arxiv"
year: 2025
bibkey: li2025too
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02678'}
tags: ['Attention Mechanism', 'Agentic', 'RAG', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) have recently achieved remarkable progress by leveraging Reinforcement Learning and extended Chain-of-Thought (CoT) techniques. However, the challenge of performing efficient language reasoning--especially during inference with extremely long outputs--has drawn increasing attention from the research community. In this work, we propose a dynamic ratio-based training pipeline that does not rely on sophisticated data annotations or interpolation between multiple models. We continuously balance the weights between the model's System-1 and System-2 data to eliminate redundant reasoning processes while preserving the model's reasoning capability. We validate our approach across models on DeepSeek-R1-Distill-7B and DeepSeek-R1-Distill-14B and on a diverse set of benchmarks with varying difficulty levels. Our method significantly reduces the number of output tokens by nearly 40% while maintaining the accuracy of the reasoning. Our code and data will be available soon.
