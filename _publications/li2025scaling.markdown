---
layout: publication
title: 'Torl: Scaling Tool-integrated RL'
authors: Xuefeng Li, Haoyang Zou, Pengfei Liu
conference: "Arxiv"
year: 2025
bibkey: li2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23383"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
We introduce ToRL (Tool-Integrated Reinforcement Learning), a framework for
training large language models (LLMs) to autonomously use computational tools
via reinforcement learning. Unlike supervised fine-tuning, ToRL allows models
to explore and discover optimal strategies for tool use. Experiments with
Qwen2.5-Math models show significant improvements: ToRL-7B reaches 43.3%
accuracy on AIME~24, surpassing reinforcement learning without tool integration
by 14% and the best existing Tool-Integrated Reasoning (TIR) model by 17%.
Further analysis reveals emergent behaviors such as strategic tool invocation,
self-regulation of ineffective code, and dynamic adaptation between
computational and analytical reasoning, all arising purely through
reward-driven learning.
