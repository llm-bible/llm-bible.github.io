---
layout: publication
title: 'Cottention: Linear Transformers With Cosine Attention'
authors: Gabriel Mongaras, Trevor Dohm, Eric C. Larson
conference: "Arxiv"
year: 2024
bibkey: mongaras2024linear
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.18747'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'BERT', 'Model Architecture', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Attention mechanisms, particularly softmax attention, have been instrumental
in the success of transformer-based models such as GPT. However, the quadratic
memory complexity of softmax attention with respect to sequence length poses
significant challenges for processing longer sequences. We introduce
Cottention, a novel attention mechanism that replaces the softmax operation
with cosine similarity. By leveraging the properties of cosine similarity and
rearranging the attention equation, Cottention achieves native linear memory
complexity with respect to sequence length, making it inherently more
memory-efficient than softmax attention. We demonstrate that Cottention can be
reformulated as a recurrent neural network (RNN) with a finite hidden state,
allowing for constant memory usage during inference. We evaluate Cottention on
both the bidirectional BERT and causal GPT tasks, demonstrating comparable
performance to softmax attention while significantly reducing memory
requirements. To ensure efficient computation, we develop a custom CUDA kernel
for Cottention. Our results show that Cottention is a promising alternative to
softmax attention, enabling the processing of longer sequences without
sacrificing performance, due to its native linear memory complexity and ability
to maintain a constant memory footprint during inference.
