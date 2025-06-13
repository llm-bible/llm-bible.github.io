---
layout: publication
title: 'Logic-of-thought: Empowering Large Language Models With Logic Programs For Solving Puzzles In Natural Language'
authors: Naiqi Li, Peiyuan Liu, Zheng Liu, Tao Dai, Yong Jiang, Shu-tao Xia
conference: "Arxiv"
year: 2025
bibkey: li2025logic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16114"}
  - {name: "Code", url: "https://github.com/naiqili/Logic-of-Thought"}
tags: ['RAG', 'Tools', 'Has Code', 'Applications']
---
Solving puzzles in natural language poses a long-standing challenge in AI. While large language models (LLMs) have recently shown impressive capabilities in a variety of tasks, they continue to struggle with complex puzzles that demand precise reasoning and exhaustive search. In this paper, we propose Logic-of-Thought (Logot), a novel framework that bridges LLMs with logic programming to address this problem. Our method leverages LLMs to translate puzzle rules and states into answer set programs (ASPs), the solution of which are then accurately and efficiently inferred by an ASP interpreter. This hybrid approach combines the natural language understanding of LLMs with the precise reasoning capabilities of logic programs. We evaluate our method on various grid puzzles and dynamic puzzles involving actions, demonstrating near-perfect accuracy across all tasks. Our code and data are available at: https://github.com/naiqili/Logic-of-Thought.
