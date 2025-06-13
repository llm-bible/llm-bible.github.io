---
layout: publication
title: 'Thinking Fast And Right: Balancing Accuracy And Reasoning Length With Adaptive Rewards'
authors: Jinyan Su, Claire Cardie
conference: "Arxiv"
year: 2025
bibkey: su2025thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18298"}
tags: ['Agentic', 'RAG', 'Tools', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated strong reasoning abilities in mathematical tasks, often enhanced through reinforcement learning (RL). However, RL-trained models frequently produce unnecessarily long reasoning traces -- even for simple queries -- leading to increased inference costs and latency. While recent approaches attempt to control verbosity by adding length penalties to the reward function, these methods rely on fixed penalty terms that are hard to tune and cannot adapt as the model's reasoning capability evolves, limiting their effectiveness. In this work, we propose an adaptive reward-shaping method that enables LLMs to "think fast and right" -- producing concise outputs without sacrificing correctness. Our method dynamically adjusts the reward trade-off between accuracy and response length based on model performance: when accuracy is high, the length penalty increases to encourage faster length reduction; when accuracy drops, the penalty is relaxed to preserve correctness. This adaptive reward accelerates early-stage length reduction while avoiding over-compression in later stages. Experiments across multiple datasets show that our approach consistently and dramatically reduces reasoning length while largely maintaining accuracy, offering a new direction for cost-efficient adaptive reasoning in large-scale language models.
