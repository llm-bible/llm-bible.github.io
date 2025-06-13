---
layout: publication
title: 'Full-stack Optimized Large Language Models For Lifelong Sequential Behavior Comprehension In Recommendation'
authors: Rong Shan, Jiachen Zhu, Jianghao Lin, Chenxu Zhu, Bo Chen, Ruiming Tang, Yong Yu, Weinan Zhang
conference: "Arxiv"
year: 2025
bibkey: shan2025full
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13344"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Prompting']
---
In this paper, we address the lifelong sequential behavior incomprehension
problem in large language models (LLMs) for recommendation, where LLMs struggle
to extract useful information from long user behavior sequences, even within
their context limits. To tackle this, we propose ReLLaX (Retrieval-enhanced
Large Language models Plus), a framework offering optimization across data,
prompt, and parameter levels. At the data level, we introduce Semantic User
Behavior Retrieval (SUBR) to reduce sequence heterogeneity, making it easier
for LLMs to extract key information. For prompt-level enhancement, we employ
Soft Prompt Augmentation (SPA) to inject collaborative knowledge, aligning item
representations with recommendation tasks and improving LLMs's exploration of
item relationships. Finally, at the parameter level, we propose Component
Fully-interactive LoRA (CFLoRA), which enhances LoRA's expressiveness by
enabling interactions between its components, allowing better capture of
sequential information. Moreover, we present new perspectives to compare
current LoRA-based LLM4Rec methods, i.e. from both a composite and a decomposed
view. We theoretically demonstrate that the ways they employ LoRA for
recommendation are degraded versions of our CFLoRA, with different constraints
on atom component interactions. Extensive experiments on three public datasets
demonstrate ReLLaX's superiority over existing baselines and its ability to
mitigate lifelong sequential behavior incomprehension effectively.
