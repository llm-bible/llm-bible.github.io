---
layout: publication
title: 'Evaluating And Advancing Multimodal Large Language Models In Perception Ability Lens'
authors: Feng Chen, Chenhui Gou, Jing Liu, Yang Yang, Zhaoyang Li, Jiyuan Zhang, Zhenbang Sun, Bohan Zhuang, Qi Wu
conference: "Arxiv"
year: 2024
bibkey: chen2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14725"}
  - {name: "Code", url: "https://github.com/Chenfeng1271/AbilityLens"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
As multimodal large language models (MLLMs) advance rapidly, rigorous evaluation has become essential, providing further guidance for their development. In this work, we focus on a unified and robust evaluation of \textbf\{vision perception\} abilities, the foundational skill of MLLMs. We find that existing perception benchmarks, each focusing on different question types, domains, and evaluation metrics, introduce significant evaluation variance, complicating comprehensive assessments of perception abilities when relying on any single benchmark. To address this, we introduce \textbf\{AbilityLens\}, a unified benchmark designed to evaluate MLLMs in six key perception abilities (ranging from counting, OCR, to understanding structural data), focusing on both accuracy and stability, with each ability encompassing diverse types of questions, domains, and metrics. With the assistance of AbilityLens, we: (1) identify the strengths and weaknesses of current main-stream MLLMs, highlighting stability patterns and revealing a notable performance gap between state-of-the-art open-source and closed-source models; (2) uncover interesting ability conflict and early convergence phenomena during MLLM training; (3) reveal the primary reason of ability conflict is data mixing ratio and LLM model size; and (4) discuss the effectiveness of some straightforward strategies \eg, fine-tuning and model merging, to solve the ability conflict. The benchmark and online leaderboard is released in https://github.com/Chenfeng1271/AbilityLens.
