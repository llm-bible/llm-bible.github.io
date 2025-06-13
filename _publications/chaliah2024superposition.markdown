---
layout: publication
title: 'Superposition In Transformers: A Novel Way Of Building Mixture Of Experts'
authors: Ayoub Ben Chaliah, Hela Dellagi
conference: "Arxiv"
year: 2024
bibkey: chaliah2024superposition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00530"}
tags: ['Fine-Tuning', 'Transformer', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Catastrophic forgetting remains a major challenge when adapting large
language models (LLMs) to new tasks or domains. Conventional fine-tuning often
overwrites existing knowledge, causing performance degradation on original
tasks. We introduce Superposition in Transformers, a novel architecture that
leverages autoencoders to superimpose the hidden representations of a base
model and a fine-tuned model within a shared parameter space. By using
B-spline-based blending coefficients and autoencoders that adaptively
reconstruct hidden states based on the input data distribution, our method
effectively mitigates catastrophic forgetting and enables a new paradigm of
"in-model" superposition. This approach preserves original model capabilities
while allowing compact domain-specific expertise to be added, and it supports
dynamic switching between model states during inference.
