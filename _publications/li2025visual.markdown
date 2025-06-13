---
layout: publication
title: 'Todre: Visual Token Pruning Via Diversity And Task Awareness For Efficient Large Vision-language Models'
authors: Duo Li, Zuhao Yang, Shijian Lu
conference: "Arxiv"
year: 2025
bibkey: li2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18757"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Tools', 'Pruning', 'Attention Mechanism']
---
The representation of visual inputs of large vision-language models (LVLMs) usually involves substantially more tokens than that of textual inputs, leading to significant computational overhead. Several recent studies strive to mitigate this issue by either conducting token compression to prune redundant visual tokens or guiding them to bypass certain computational stages. While most existing work exploits token importance as the redundancy indicator, our study reveals that two largely neglected factors, namely, the diversity of retained visual tokens and their task relevance, often offer more robust criteria in token pruning. To this end, we design ToDRE, a two-stage and training-free token compression framework that achieves superior performance by pruning Tokens based on token Diversity and token-task RElevance. Instead of pruning redundant tokens, ToDRE introduces a greedy k-center algorithm to select and retain a small subset of diverse visual tokens after the vision encoder. Additionally, ToDRE addresses the "information migration" by further eliminating task-irrelevant visual tokens within the decoder of large language model (LLM). Extensive experiments show that ToDRE effectively reduces 90% of visual tokens after vision encoder and adaptively prunes all visual tokens within certain LLM's decoder layers, leading to a 2.6x speed-up in total inference time while maintaining 95.1% of model performance and excellent compatibility with efficient attention operators.
