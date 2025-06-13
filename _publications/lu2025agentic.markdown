---
layout: publication
title: 'Octotools: An Agentic Framework With Extensible Tools For Complex Reasoning'
authors: Pan Lu, Bowen Chen, Sheng Liu, Rahul Thapa, Joseph Boen, James Zou
conference: "Arxiv"
year: 2025
bibkey: lu2025agentic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11271'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT']
---
Solving complex reasoning tasks may involve visual understanding, domain
knowledge retrieval, numerical calculation, and multi-step reasoning. Existing
methods augment large language models (LLMs) with external tools but are
restricted to specialized domains, limited tool types, or require additional
training data. In this paper, we introduce OctoTools, a training-free,
user-friendly, and easily extensible open-source agentic framework designed to
tackle complex reasoning across diverse domains. OctoTools introduces
standardized tool cards to encapsulate tool functionality, a planner for both
high-level and low-level planning, and an executor to carry out tool usage. We
validate OctoTools' generality across 16 diverse tasks (including MathVista,
MMLU-Pro, MedQA, and GAIA-Text), achieving substantial average accuracy gains
of 9.3% over GPT-4o. Furthermore, OctoTools outperforms AutoGen, GPT-Functions
and LangChain by up to 10.6% when given the same set of tools. Through
comprehensive analysis and ablations, OctoTools demonstrates advantages in task
planning, effective tool usage, and multi-step problem solving.
