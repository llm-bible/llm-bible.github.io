---
layout: publication
title: 'How Numerical Precision Affects Mathematical Reasoning Capabilities Of Llms'
authors: Guhao Feng, Kai Yang, Yuntian Gu, Xinyue Ai, Shengjie Luo, Jiacheng Sun, Di He, Zhenguo Li, Liwei Wang
conference: "Arxiv"
year: 2024
bibkey: feng2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13857"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer', 'Reinforcement Learning']
---
Despite the remarkable success of Transformer-based Large Language Models
(LLMs) across various domains, understanding and enhancing their mathematical
capabilities remains a significant challenge. In this paper, we conduct a
rigorous theoretical analysis of LLMs' mathematical abilities, with a specific
focus on their arithmetic performances. We identify numerical precision as a
key factor that influences their effectiveness in mathematical tasks. Our
results show that Transformers operating with low numerical precision fail to
address arithmetic tasks, such as iterated addition and integer multiplication,
unless the model size grows super-polynomially with respect to the input
length. In contrast, Transformers with standard numerical precision can
efficiently handle these tasks with significantly smaller model sizes. We
further support our theoretical findings through empirical experiments that
explore the impact of varying numerical precision on arithmetic tasks,
providing valuable insights for improving the mathematical reasoning
capabilities of LLMs.
