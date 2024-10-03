---
layout: publication
title: 'Llmembed: Rethinking Lightweight Llm''s Genuine Function In Text Classification'
authors: Liu Chun, Zhang Hongguang, Zhao Kainan, Ju Xinghai, Yang Lin
conference: "Arxiv"
year: 2024
bibkey: liu2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03725"}
  - {name: "Code", url: "https://github.com/ChunLiu-cs/LLMEmbed-ACL2024"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
With the booming of Large Language Models (LLMs), prompt-learning has become a promising method mainly researched in various research areas. Recently, many attempts based on prompt-learning have been made to improve the performance of text classification. However, most of these methods are based on heuristic Chain-of-Thought (CoT), and tend to be more complex but less efficient. In this paper, we rethink the LLM-based text classification methodology, propose a simple and effective transfer learning strategy, namely LLMEmbed, to address this classical but challenging task. To illustrate, we first study how to properly extract and fuse the text embeddings via various lightweight LLMs at different network depths to improve their robustness and discrimination, then adapt such embeddings to train the classifier. We perform extensive experiments on publicly available datasets, and the results show that LLMEmbed achieves strong performance while enjoys low training overhead using lightweight LLM backbones compared to recent methods based on larger LLMs, i.e. GPT-3, and sophisticated prompt-based strategies. Our LLMEmbed achieves adequate accuracy on publicly available benchmarks without any fine-tuning while merely use 4&#37; model parameters, 1.8&#37; electricity consumption and 1.5&#37; runtime compared to its counterparts. Code is available at: https://github.com/ChunLiu-cs/LLMEmbed-ACL2024.
