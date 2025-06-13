---
layout: publication
title: 'Quantifying Logical Consistency In Transformers Via Query-key Alignment'
authors: Eduard Tulchinskii, Anastasia Voznyuk, Laida Kushnareva, Andrei Andriiainen, Irina Piontkovskaya, Evgeny Burnaev, Serguei Barannikov
conference: "Arxiv"
year: 2025
bibkey: tulchinskii2025quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17017"}
tags: ['Security', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Prompting', 'Attention Mechanism']
---
Large language models (LLMs) have demonstrated impressive performance in
various natural language processing tasks, yet their ability to perform
multi-step logical reasoning remains an open challenge. Although
Chain-of-Thought prompting has improved logical reasoning by enabling models to
generate intermediate steps, it lacks mechanisms to assess the coherence of
these logical transitions. In this paper, we propose a novel, lightweight
evaluation strategy for logical reasoning that uses query-key alignments inside
transformer attention heads. By computing a single forward pass and extracting
a "QK-score" from carefully chosen heads, our method reveals latent
representations that reliably separate valid from invalid inferences, offering
a scalable alternative to traditional ablation-based techniques. We also
provide an empirical validation on multiple logical reasoning benchmarks,
demonstrating improved robustness of our evaluation method against distractors
and increased reasoning depth. The experiments were conducted on a diverse set
of models, ranging from 1.5B to 70B parameters.
