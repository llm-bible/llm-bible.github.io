---
layout: publication
title: 'CORD: Balancing Consistency And Rank Distillation For Robust Retrieval-augmented Generation'
authors: Youngwon Lee, Seung-won Hwang, Daniel Campos, Filip Graliński, Zhewei Yao, Yuxiong He
conference: "Arxiv"
year: 2024
bibkey: lee2024balancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14581"}
tags: ['Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Training Techniques', 'Distillation']
---
With the adoption of retrieval-augmented generation (RAG), large language
models (LLMs) are expected to ground their generation to the retrieved
contexts. Yet, this is hindered by position bias of LLMs, failing to evenly
attend to all contexts. Previous work has addressed this by synthesizing
contexts with perturbed positions of gold segment, creating a
position-diversified train set. We extend this intuition to propose consistency
regularization with augmentation and distillation. First, we augment each
training instance with its position perturbation to encourage consistent
predictions, regardless of ordering. We also distill behaviors of this pair,
although it can be counterproductive in certain RAG scenarios where the given
order from the retriever is crucial for generation quality. We thus propose
CORD, balancing COnsistency and Rank Distillation. CORD adaptively samples
noise-controlled perturbations from an interpolation space, ensuring both
consistency and respect for the rank prior. Empirical results show this balance
enables CORD to outperform consistently in diverse RAG benchmarks.
