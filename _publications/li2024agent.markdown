---
layout: publication
title: 'Codetree: Agent-guided Tree Search For Code Generation With Large Language Models'
authors: Jierui Li, Hung Le, Yingbo Zhou, Caiming Xiong, Silvio Savarese, Doyen Sahoo
conference: "Arxiv"
year: 2024
bibkey: li2024agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.04329"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Tools', 'Applications', 'Model Architecture']
---
Pre-trained on massive amounts of code and text data, large language models
(LLMs) have demonstrated remarkable achievements in performing code generation
tasks. With additional execution-based feedback, these models can act as agents
with capabilities to self-refine and improve generated code autonomously.
However, on challenging coding tasks with extremely large search space, current
agentic approaches still struggle with multi-stage planning, generating, and
debugging. To address this problem, we propose CodeTree, a framework for LLM
agents to efficiently explore the search space in different stages of the code
generation process. Specifically, we adopted a unified tree structure to
explicitly explore different coding strategies, generate corresponding coding
solutions, and subsequently refine the solutions. In each stage, critical
decision-making (ranking, termination, expanding) of the exploration process is
guided by both the environmental execution-based feedback and
LLM-agent-generated feedback. We comprehensively evaluated CodeTree on 7 code
generation benchmarks and demonstrated the significant performance gains of
CodeTree against strong baselines. Using GPT-4o as the base model, we
consistently achieved top results of 95.1 on HumanEval, 98.7 on MBPP, and 43.0
on CodeContests. On the challenging SWEBench benchmark, our approach led to
significant performance gains.
