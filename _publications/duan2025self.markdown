---
layout: publication
title: 'ORPP: Self-optimizing Role-playing Prompts To Enhance Language Model Capabilities'
authors: Yifan Duan, Yihong Tang, Kehai Chen, Liqiang Nie, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: duan2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02480"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Few-Shot', 'Tools', 'RAG', 'Prompting']
---
High-quality prompts are crucial for eliciting outstanding performance from large language models (LLMs) on complex tasks. Existing research has explored model-driven strategies for prompt optimization. However, these methods often suffer from high computational overhead or require strong optimization capabilities from the model itself, which limits their broad applicability.To address these challenges, we propose ORPP (Optimized Role-Playing Prompt),a framework that enhances model performance by optimizing and generating role-playing prompts. The core idea of ORPP is to confine the prompt search space to role-playing scenarios, thereby fully activating the model's intrinsic capabilities through carefully crafted, high-quality role-playing prompts. Specifically, ORPP first performs iterative optimization on a small subset of training samples to generate high-quality role-playing prompts. Then, leveraging the model's few-shot learning capability, it transfers the optimization experience to efficiently generate suitable prompts for the remaining samples.Our experimental results show that ORPP not only matches but in most cases surpasses existing mainstream prompt optimization methods in terms of performance. Notably, ORPP demonstrates superior "plug-and-play" capability. In most cases, it can be integrated with various other prompt methods and further enhance their effectiveness.
