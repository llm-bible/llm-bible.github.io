---
layout: publication
title: 'LLM Pretraining With Continuous Concepts'
authors: Jihoon Tack, Jack Lanchantin, Jane Yu, Andrew Cohen, Ilia Kulikov, Janice Lan, Shibo Hao, Yuandong Tian, Jason Weston, Xian Li
conference: "Arxiv"
year: 2025
bibkey: tack2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08524"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'Distillation', 'Pretraining Methods', 'Interpretability and Explainability']
---
Next token prediction has been the standard training objective used in large
language model pretraining. Representations are learned as a result of
optimizing for token-level perplexity. We propose Continuous Concept Mixing
(CoCoMix), a novel pretraining framework that combines discrete next token
prediction with continuous concepts. Specifically, CoCoMix predicts continuous
concepts learned from a pretrained sparse autoencoder and mixes them into the
model's hidden state by interleaving with token hidden representations. Through
experiments on multiple benchmarks, including language modeling and downstream
reasoning tasks, we show that CoCoMix is more sample efficient and consistently
outperforms standard next token prediction, knowledge distillation and
inserting pause tokens. We find that combining both concept learning and
interleaving in an end-to-end framework is critical to performance gains.
Furthermore, CoCoMix enhances interpretability and steerability by allowing
direct inspection and modification of the predicted concept, offering a
transparent way to guide the model's internal reasoning process.
