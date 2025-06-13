---
layout: publication
title: 'From Sparse Dependence To Sparse Attention: Unveiling How Chain-of-thought Enhances Transformer Sample Efficiency'
authors: Kaiyue Wen, Huaqing Zhang, Hongzhou Lin, Jingzhao Zhang
conference: "Arxiv"
year: 2024
bibkey: wen2024from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05459'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Chain-of-thought (CoT) significantly enhances the reasoning performance of
large language models (LLM). While current theoretical studies often attribute
this improvement to increased expressiveness and computational capacity, we
argue that expressiveness is not the primary limitation in the LLM regime, as
current large models will fail on simple tasks. Using a parity-learning setup,
we demonstrate that CoT can substantially improve sample efficiency even when
the representation power is sufficient. Specifically, with CoT, a transformer
can learn the function within polynomial samples, whereas without CoT, the
required sample size is exponential. Additionally, we show that CoT simplifies
the learning process by introducing sparse sequential dependencies among input
tokens, and leads to a sparse and interpretable attention. We validate our
theoretical analysis with both synthetic and real-world experiments, confirming
that sparsity in attention layers is a key factor of the improvement induced by
CoT.
