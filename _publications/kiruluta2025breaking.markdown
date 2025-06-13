---
layout: publication
title: 'Breaking Quadratic Barriers: A Non-attention LLM For Ultra-long Context Horizons'
authors: Andrew Kiruluta, Preethi Raju, Priscilla Burity
conference: "Arxiv"
year: 2025
bibkey: kiruluta2025breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01963"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
We present a novel non attention based architecture for large language models (LLMs) that efficiently handles very long context windows, on the order of hundreds of thousands to potentially millions of tokens. Unlike traditional Transformer designs, which suffer from quadratic memory and computation overload due to the nature of the self attention mechanism, our model avoids token to token attention entirely. Instead, it combines the following complementary components: State Space blocks (inspired by S4) that learn continuous time convolution kernels and scale near linearly with sequence length, Multi Resolution Convolution layers that capture local context at different dilation levels, a lightweight Recurrent Supervisor to maintain a global hidden state across sequential chunks, and Retrieval Augmented External Memory that stores and retrieves high-level chunk embeddings without reintroducing quadratic operations.
