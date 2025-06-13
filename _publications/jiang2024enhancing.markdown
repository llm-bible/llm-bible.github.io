---
layout: publication
title: 'Enhancing LLM Reasoning With Reward-guided Tree Search'
authors: Jinhao Jiang, Zhipeng Chen, Yingqian Min, Jie Chen, Xiaoxue Cheng, Jiapeng Wang, Yiru Tang, Haoxiang Sun, Jia Deng, Wayne Xin Zhao, Zheng Liu, Dong Yan, Jian Xie, Zhongyuan Wang, Ji-rong Wen
conference: "Arxiv"
year: 2024
bibkey: jiang2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.11694"}
tags: ['Fine-Tuning', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism']
---
Recently, test-time scaling has garnered significant attention from the
research community, largely due to the substantial advancements of the o1 model
released by OpenAI. By allocating more computational resources during the
inference phase, large language models~(LLMs) can extensively explore the
solution space by generating more thought tokens or diverse solutions, thereby
producing more accurate responses. However, developing an o1-like reasoning
approach is challenging, and researchers have been making various attempts to
advance this open area of research. In this paper, we present a preliminary
exploration into enhancing the reasoning abilities of LLMs through
reward-guided tree search algorithms. This framework is implemented by
integrating the policy model, reward model, and search algorithm. It is
primarily constructed around a tree search algorithm, where the policy model
navigates a dynamically expanding tree guided by a specially trained reward
model. The implemented framework is denoted as \textbf\{STILL-1\}. We thoroughly
explore various design considerations necessary for implementing this framework
and provide a detailed report of the technical aspects. To assess the
effectiveness of our approach, we focus on mathematical reasoning tasks and
conduct extensive evaluations on four challenging datasets, significantly
enhancing the reasoning abilities of LLMs.
