---
layout: publication
title: 'LLM4EFFI: Leveraging Large Language Models To Enhance Code Efficiency And Correctness'
authors: Tong Ye, Weigang Huang, Xuhong Zhang, Tengfei Ma, Peiyu Liu, Jianwei Yin, Wenhai Wang
conference: "Arxiv"
year: 2025
bibkey: ye2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18489"}
tags: ['Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Applications']
---
Large Language Models (LLMs), particularly Code LLMs, have demonstrated
impressive performance in code generation. Current research primarily focuses
on the correctness of generated code, while efficiency remains less explored.
Recent works have focused on modifying the initial version of the code to
improve its efficiency. However, such refinements are limited by the
algorithmic design and overall logic of the initial code, resulting in only
incremental improvements. In contrast, when human developers write high-quality
code, they typically begin by designing several potential solutions at the
logical level, evaluating various algorithms and their complexities, and then
proceeding to implement and optimize the solution. In this study, we introduce
\tool: \uline\{L\}arge \uline\{L\}anguage \uline\{M\}odel for Code
\uline\{Effi\}ciency, a novel framework that enables LLMs to generate code that
balances both efficiency and correctness. Specifically, \tool divides the
efficiency optimization process into two domains: algorithmic exploration in
the logic domain and implementation optimization in the code domain. The
correctness of the code is then guaranteed through a synthetic test case
refinement process. This approach, which prioritizes efficiency before ensuring
correctness, offers a new paradigm for efficient code generation. Experiments
demonstrate that \tool consistently improves both efficiency and correctness,
achieving new state-of-the-art performance in code efficiency benchmarks across
various LLM backbones.
