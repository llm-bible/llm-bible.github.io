---
layout: publication
title: 'FABLE: A Novel Data-flow Analysis Benchmark On Procedural Text For Large Language Model Evaluation'
authors: Vishal Pallagani, Nitin Gupta, John Aydin, Biplav Srivastava
conference: "Arxiv"
year: 2025
bibkey: pallagani2025novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24258"}
tags: ['Prompting', 'Reinforcement Learning']
---
Understanding how data moves, transforms, and persists, known as data flow, is fundamental to reasoning in procedural tasks. Despite their fluency in natural and programming languages, large language models (LLMs), although increasingly being applied to decisions with procedural tasks, have not been systematically evaluated for their ability to perform data-flow reasoning. We introduce FABLE, an extensible benchmark designed to assess LLMs' understanding of data flow using structured, procedural text. FABLE adapts eight classical data-flow analyses from software engineering: reaching definitions, very busy expressions, available expressions, live variable analysis, interval analysis, type-state analysis, taint analysis, and concurrency analysis. These analyses are instantiated across three real-world domains: cooking recipes, travel routes, and automated plans. The benchmark includes 2,400 question-answer pairs, with 100 examples for each domain-analysis combination. We evaluate three types of LLMs: a reasoning-focused model (DeepSeek-R1 8B), a general-purpose model (LLaMA 3.1 8B), and a code-specific model (Granite Code 8B). Each model is tested using majority voting over five sampled completions per prompt. Results show that the reasoning model achieves higher accuracy, but at the cost of over 20 times slower inference compared to the other models. In contrast, the general-purpose and code-specific models perform close to random chance. FABLE provides the first diagnostic benchmark to systematically evaluate data-flow reasoning and offers insights for developing models with stronger procedural understanding.
