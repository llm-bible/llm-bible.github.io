---
layout: publication
title: 'Filling Memory Gaps: Enhancing Continual Semantic Parsing Via SQL Syntax Variance-guided Llms Without Real Data Replay'
authors: Ruiheng Liu, Jinyu Zhang, Yanqi Song, Yu Zhang, Bailong Yang
conference: "Arxiv"
year: 2024
bibkey: liu2024filling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07246"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Distillation']
---
Continual Semantic Parsing (CSP) aims to train parsers to convert natural
language questions into SQL across tasks with limited annotated examples,
adapting to the real-world scenario of dynamically updated databases. Previous
studies mitigate this challenge by replaying historical data or employing
parameter-efficient tuning (PET), but they often violate data privacy or rely
on ideal continual learning settings. To address these problems, we propose a
new Large Language Model (LLM)-Enhanced Continuous Semantic Parsing method,
named LECSP, which alleviates forgetting while encouraging generalization,
without requiring real data replay or ideal settings. Specifically, it first
analyzes the commonalities and differences between tasks from the SQL syntax
perspective to guide LLMs in reconstructing key memories and improving memory
accuracy through a calibration strategy. Then, it uses a task-aware
dual-teacher distillation framework to promote the accumulation and transfer of
knowledge during sequential training. Experimental results on two CSP
benchmarks show that our method significantly outperforms existing methods,
even those utilizing data replay or ideal settings. Additionally, we achieve
generalization performance beyond the upper limits, better adapting to unseen
tasks.
