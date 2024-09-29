---
layout: publication
title: Llmembed Rethinking Lightweight Llms Genuine Function In Text Classification
authors: Liu Chun, Zhang Hongguang, Zhao Kainan, Ju Xinghai, Yang Lin
conference: "Arxiv"
year: 2024
bibkey: liu2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03725"}
  - {name: "Code", url: "https://github.com/ChunLiu&#45;cs/LLMEmbed&#45;ACL2024"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
With the booming of Large Language Models (LLMs) prompt45;learning has become a promising method mainly researched in various research areas. Recently many attempts based on prompt45;learning have been made to improve the performance of text classification. However most of these methods are based on heuristic Chain45;of45;Thought (CoT) and tend to be more complex but less efficient. In this paper we rethink the LLM45;based text classification methodology propose a simple and effective transfer learning strategy namely LLMEmbed to address this classical but challenging task. To illustrate we first study how to properly extract and fuse the text embeddings via various lightweight LLMs at different network depths to improve their robustness and discrimination then adapt such embeddings to train the classifier. We perform extensive experiments on publicly available datasets and the results show that LLMEmbed achieves strong performance while enjoys low training overhead using lightweight LLM backbones compared to recent methods based on larger LLMs i.e. GPT45;3 and sophisticated prompt45;based strategies. Our LLMEmbed achieves adequate accuracy on publicly available benchmarks without any fine45;tuning while merely use 437; model parameters 1.837; electricity consumption and 1.537; runtime compared to its counterparts. Code is available at https://github.com/ChunLiu&#45;cs/LLMEmbed&#45;ACL2024.
