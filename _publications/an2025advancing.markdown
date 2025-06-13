---
layout: publication
title: 'Ultraif: Advancing Instruction Following From The Wild'
authors: Kaikai An, Li Sheng, Ganqu Cui, Shuzheng Si, Ning Ding, Yu Cheng, Baobao Chang
conference: "Arxiv"
year: 2025
bibkey: an2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04153"}
  - {name: "Code", url: "https://github.com/kkk-an/UltraIF"}
tags: ['Prompting', 'Applications', 'Has Code', 'Reinforcement Learning']
---
Instruction-following made modern large language models (LLMs) helpful
assistants. However, the key to taming LLMs on complex instructions remains
mysterious, for that there are huge gaps between models trained by open-source
community and those trained by leading companies. To bridge the gap, we propose
a simple and scalable approach UltraIF for building LLMs that can follow
complex instructions with open-source data. UltraIF first decomposes real-world
user prompts into simpler queries, constraints, and corresponding evaluation
questions for the constraints. Then, we train an UltraComposer to compose
constraint-associated prompts with evaluation questions. This prompt composer
allows us to synthesize complicated instructions as well as filter responses
with evaluation questions. In our experiment, for the first time, we
successfully align LLaMA-3.1-8B-Base to catch up with its instruct version on 5
instruction-following benchmarks without any benchmark information, using only
8B model as response generator and evaluator. The aligned model also achieved
competitive scores on other benchmarks. Moreover, we also show that UltraIF
could further improve LLaMA-3.1-8B-Instruct through self-alignment, motivating
broader use cases for the method. Our code will be available at
https://github.com/kkk-an/UltraIF.
