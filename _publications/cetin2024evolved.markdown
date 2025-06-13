---
layout: publication
title: 'An Evolved Universal Transformer Memory'
authors: Edoardo Cetin, Qi Sun, Tianyu Zhao, Yujin Tang
conference: "Arxiv"
year: 2024
bibkey: cetin2024evolved
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13166"}
tags: ['Transformer', 'Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
Prior methods propose to offset the escalating costs of modern foundation
models by dropping specific parts of their contexts with hand-designed rules,
while attempting to preserve their original performance. We overcome this
trade-off with Neural Attention Memory Models (NAMMs), introducing a learned
network for memory management that improves both the performance and efficiency
of transformers. We evolve NAMMs atop pre-trained transformers to provide
different latent contexts focusing on the most relevant information for
individual layers and attention heads. NAMMs are universally applicable to any
model using self-attention as they condition exclusively on the values in the
produced attention matrices. Learning NAMMs on a small set of problems, we
achieve substantial performance improvements across multiple long-context
benchmarks while cutting the model's input contexts up to a fraction of the
original sizes. We show the generality of our conditioning enables zero-shot
transfer of NAMMs trained only on language to entirely new transformer
architectures even across input modalities, with their benefits carrying over
to vision and reinforcement learning.
