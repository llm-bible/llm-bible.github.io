---
layout: publication
title: ARGS Alignment As Reward-guided Search
authors: Khanov Maxim, Burapacheep Jirayu, Li Yixuan
conference: "Arxiv"
year: 2024
bibkey: khanov2024alignment
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01694"}
  - {name: "Code", url: "https://github.com/deeplearning-wisc/args"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Aligning large language models with human objectives is paramount yet common approaches including RLHF suffer from unstable and resource-intensive training. In response to this challenge we introduce ARGS Alignment as Reward-Guided Search a novel framework that integrates alignment into the decoding process eliminating the need for expensive RL training. By adjusting the models probabilistic predictions using a reward signal ARGS generates texts with semantic diversity while being aligned with human preferences offering a promising and flexible solution for aligning language models. Notably ARGS demonstrates consistent enhancements in average reward compared to baselines across diverse alignment tasks and various model dimensions. For example under the same greedy-based decoding strategy our method improves the average reward by 19.5637; relative to the baseline and secures a preference or tie score of 64.3337; in GPT-4 evaluation. We believe that our framework emphasizing decoding-time alignment paves the way for more responsive language models in the future. Code is publicly available at (url)https://github.com/deeplearning-wisc/args\}.
