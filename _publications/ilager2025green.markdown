---
layout: publication
title: 'GREEN-CODE: Learning To Optimize Energy Efficiency In Llm-based Code Generation'
authors: Shashikant Ilager, Lukas Florian Briem, Ivona Brandic
conference: "Arxiv"
year: 2025
bibkey: ilager2025green
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.11006'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs) are becoming integral to daily life, showcasing
their vast potential across various Natural Language Processing (NLP) tasks.
Beyond NLP, LLMs are increasingly used in software development tasks, such as
code completion, modification, bug fixing, and code translation. Software
engineers widely use tools like GitHub Copilot and Amazon Q, streamlining
workflows and automating tasks with high accuracy. While the resource and
energy intensity of LLM training is often highlighted, inference can be even
more resource-intensive over time, as it's a continuous process with a high
number of invocations. Therefore, developing resource-efficient alternatives
for LLM inference is crucial for sustainability. This work proposes GREEN-CODE,
a framework for energy-aware code generation in LLMs. GREEN-CODE performs
dynamic early exit during LLM inference. We train a Reinforcement Learning (RL)
agent that learns to balance the trade-offs between accuracy, latency, and
energy consumption. Our approach is evaluated on two open-source LLMs, Llama
3.2 3B and OPT 2.7B, using the JavaCorpus and PY150 datasets. Results show that
our method reduces the energy consumption between 23-50 % on average for code
generation tasks without significantly affecting accuracy.
