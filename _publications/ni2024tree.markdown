---
layout: publication
title: 'Tree-of-code: A Tree-structured Exploring Framework For End-to-end Code Generation And Execution In Complex Task Handling'
authors: Ziyi Ni, Yifan Li, Ning Yang, Dou Shen, Pin Lv, Daxiang Dong
conference: "Arxiv"
year: 2024
bibkey: ni2024tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15305"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Solving complex reasoning tasks is a key real-world application of agents.
Thanks to the pretraining of Large Language Models (LLMs) on code data, recent
approaches like CodeAct successfully use code as LLM agents' action, achieving
good results. However, CodeAct greedily generates the next action's code block
by relying on fragmented thoughts, resulting in inconsistency and instability.
Moreover, CodeAct lacks action-related ground-truth (GT), making its
supervision signals and termination conditions questionable in multi-turn
interactions. To address these issues, we first introduce a simple yet
effective end-to-end code generation paradigm, CodeProgram, which leverages
code's systematic logic to align with global reasoning and enable cohesive
problem-solving. Then, we propose Tree-of-Code (ToC), which self-grows
CodeProgram nodes based on the executable nature of the code and enables
self-supervision in a GT-free scenario. Experimental results on two datasets
using ten popular zero-shot LLMs show ToC remarkably boosts accuracy by nearly
20% over CodeAct with less than 1/4 turns. Several LLMs even perform better on
one-turn CodeProgram than on multi-turn CodeAct. To further investigate the
trade-off between efficacy and efficiency, we test different ToC tree sizes and
exploration mechanisms. We also highlight the potential of ToC's end-to-end
data generation for supervised and reinforced fine-tuning.
