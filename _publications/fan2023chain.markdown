---
layout: publication
title: 'Chain-of-thought Tuning: Masked Language Models Can Also Think Step By Step In Natural Language Understanding'
authors: Caoyun Fan, Jidong Tian, Yitian Li, Wenqing Chen, Hao He, Yaohui Jin
conference: "Arxiv"
year: 2023
bibkey: fan2023chain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.11721'}
tags: ['Masked Language Model', 'BERT', 'Applications', 'Tools', 'Prompting', 'Pretraining Methods']
---
Chain-of-Thought (CoT) is a technique that guides Large Language Models
(LLMs) to decompose complex tasks into multi-step reasoning through
intermediate steps in natural language form. Briefly, CoT enables LLMs to think
step by step. However, although many Natural Language Understanding (NLU) tasks
also require thinking step by step, LLMs perform less well than small-scale
Masked Language Models (MLMs). To migrate CoT from LLMs to MLMs, we propose
Chain-of-Thought Tuning (CoTT), a two-step reasoning framework based on prompt
tuning, to implement step-by-step thinking for MLMs on NLU tasks. From the
perspective of CoT, CoTT's two-step framework enables MLMs to implement task
decomposition; CoTT's prompt tuning allows intermediate steps to be used in
natural language form. Thereby, the success of CoT can be extended to NLU tasks
through MLMs. To verify the effectiveness of CoTT, we conduct experiments on
two NLU tasks: hierarchical classification and relation extraction, and the
results show that CoTT outperforms baselines and achieves state-of-the-art
performance.
