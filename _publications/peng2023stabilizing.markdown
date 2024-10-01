---
layout: publication
title: 'Stabilizing RLHF Through Advantage Model And Selective Rehearsal'
authors: Peng Baolin, Song Linfeng, Tian Ye, Jin Lifeng, Mi Haitao, Yu Dong
conference: "Arxiv"
year: 2023
bibkey: peng2023stabilizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10202"}
tags: ['Reinforcement Learning', 'Training Techniques']
---
"Large Language Models (LLMs) have revolutionized natural language processing, yet aligning these models with human values and preferences using RLHF remains a significant challenge. This challenge is characterized by various instabilities, such as reward hacking and catastrophic forgetting. In this technical report, we propose two innovations to stabilize RLHF training: 1) Advantage Model, which directly models advantage score i.e., extra reward compared to the expected rewards and regulates score distributions across tasks to prevent reward hacking. 2) Selective Rehearsal, which mitigates catastrophic forgetting by strategically selecting data for PPO training and knowledge rehearsing. Our experimental analysis on public and proprietary datasets reveals that the proposed methods not only increase stability in RLHF training but also achieve higher reward scores and win rates."
