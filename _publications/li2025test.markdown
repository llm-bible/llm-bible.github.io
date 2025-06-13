---
layout: publication
title: 'S*: Test Time Scaling For Code Generation'
authors: Dacheng Li, Shiyi Cao, Chengkun Cao, Xiuyu Li, Shangyin Tan, Kurt Keutzer, Jiarong Xing, Joseph E. Gonzalez, Ion Stoica
conference: "Arxiv"
year: 2025
bibkey: li2025test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14382"}
  - {name: "Code", url: "https://github.com/NovaSky-AI/SkyThought"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Has Code']
---
Increasing test-time compute for LLMs shows promise across domains but
remains underexplored in code generation, despite extensive study in math. In
this paper, we propose S*, the first hybrid test-time scaling framework that
substantially improves the coverage and selection accuracy of generated code.
S* extends the existing parallel scaling paradigm with sequential scaling to
push performance boundaries. It further leverages a novel selection mechanism
that adaptively generates distinguishing inputs for pairwise comparison,
combined with execution-grounded information to robustly identify correct
solutions. We evaluate across 12 Large Language Models and Large Reasoning
Model and show: (1) S* consistently improves performance across model families
and sizes, enabling a 3B model to outperform GPT-4o-mini; (2) S* enables
non-reasoning models to surpass reasoning models - GPT-4o-mini with S*
outperforms o1-preview by 3.7% on LiveCodeBench; (3) S* further boosts
state-of-the-art reasoning models - DeepSeek-R1-Distill-Qwen-32B with S*
achieves 85.7% on LiveCodeBench, approaching o1 (high) at 88.5%. Code will be
available under https://github.com/NovaSky-AI/SkyThought.
