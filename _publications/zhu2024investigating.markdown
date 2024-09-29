---
layout: publication
title: Investigating Instruction Tuning Large Language Models on Graphs
authors: Zhu Kerui, Huang Bo-wei, Jin Bowen, Jiao Yizhu, Zhong Ming, Chang Kevin, Lin Shou-de, Han Jiawei
conference: "Arxiv"
year: 2024
bibkey: zhu2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05457"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Inspired by the recent advancements of Large Language Models (LLMs) in NLP tasks theres growing interest in applying LLMs to graph-related tasks. This study delves into the capabilities of instruction-following LLMs for engaging with real-world graphs aiming to offer empirical insights into how LLMs can effectively interact with graphs and generalize across graph tasks. We begin by constructing a dataset designed for instruction tuning which comprises a diverse collection of 79 graph-related tasks from academic and e-commerce domains featuring 44240 training instances and 18960 test samples. Utilizing this benchmark our initial investigation focuses on identifying the optimal graph representation that serves as a conduit for LLMs to understand complex graph structures. Our findings indicate that JSON format for graph representation consistently outperforms natural language and code formats across various LLMs and graph types. Furthermore we examine the key factors that influence the generalization abilities of instruction-tuned LLMs by evaluating their performance on both in-domain and out-of-domain graph tasks.
