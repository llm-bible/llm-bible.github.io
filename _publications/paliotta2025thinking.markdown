---
layout: publication
title: 'Thinking Slow, Fast: Scaling Inference Compute With Distilled Reasoners'
authors: Daniele Paliotta, Junxiong Wang, Matteo Pagliardini, Kevin Y. Li, Aviv Bick, J. Zico Kolter, Albert Gu, François Fleuret, Tri Dao
conference: "Arxiv"
year: 2025
bibkey: paliotta2025thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20339"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Distillation']
---
Recent advancements have demonstrated that the performance of large language
models (LLMs) can be significantly enhanced by scaling computational resources
at test time. A common strategy involves generating multiple Chain-of-Thought
(CoT) trajectories and aggregating their outputs through various selection
mechanisms. This raises a fundamental question: can models with lower
complexity leverage their superior generation throughput to outperform
similarly sized Transformers for a fixed computational budget? To address this
question and overcome the lack of strong subquadratic reasoners, we distill
pure and hybrid Mamba models from pretrained Transformers. Trained on only 8
billion tokens, our distilled models show strong performance and scaling on
mathematical reasoning datasets while being much faster at inference for large
batches and long sequences. Despite the zero-shot performance hit due to
distillation, both pure and hybrid Mamba models can scale their coverage and
accuracy performance past their Transformer teacher models under fixed time
budgets, opening a new direction for scaling inference compute.
