---
layout: publication
title: 'Active Layer-contrastive Decoding Reduces Hallucination In Large Language Model Generation'
authors: Hongxiang Zhang, Hao Chen, Muhao Chen, Tianyi Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025active
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23657"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning']
---
Recent decoding methods improve the factuality of large language models (LLMs) by refining how the next token is selected during generation. These methods typically operate at the token level, leveraging internal representations to suppress superficial patterns. Nevertheless, LLMs remain prone to hallucinations, especially over longer contexts. In this paper, we propose Active Layer-Contrastive Decoding (ActLCD), a novel decoding strategy that actively decides when to apply contrasting layers during generation. By casting decoding as a sequential decision-making problem, ActLCD employs a reinforcement learning policy guided by a reward-aware classifier to optimize factuality beyond the token level. Our experiments demonstrate that ActLCD surpasses state-of-the-art methods across five benchmarks, showcasing its effectiveness in mitigating hallucinations in diverse generation scenarios.
