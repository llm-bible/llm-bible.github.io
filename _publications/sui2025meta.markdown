---
layout: publication
title: 'Meta-reasoner: Dynamic Guidance For Optimized Inference-time Reasoning In Large Language Models'
authors: Yuan Sui, Yufei He, Tri Cao, Simeng Han, Yulin Chen, Bryan Hooi
conference: "Arxiv"
year: 2025
bibkey: sui2025meta
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19918'}
tags: ['Reinforcement Learning', 'Tools', 'Applications']
---
Large Language Models (LLMs) increasingly rely on prolonged reasoning chains to solve complex tasks. However, this trial-and-error approach often leads to high computational overhead and error propagation, where early mistakes can derail subsequent steps. To address these issues, we introduce Meta-Reasoner, a framework that dynamically optimizes inference-time reasoning by enabling LLMs to \enquote\{think about how to think.\} Drawing inspiration from human meta-cognition and dual-process theory, Meta-Reasoner operates as a strategic advisor, decoupling high-level guidance from step-by-step generation. It employs contextual multi-armed bandits to iteratively evaluate reasoning progress and select optimal strategies (e.g., backtrack, clarify ambiguity, restart from scratch, or propose alternative approaches), and reallocates computational resources toward the most promising paths. Our evaluations on mathematical reasoning and puzzles highlight the potential of dynamic reasoning chains to overcome inherent challenges in the LLM reasoning process and also show promise in broader applications, offering a scalable and adaptable solution for reasoning-intensive tasks.
