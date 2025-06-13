---
layout: publication
title: 'Millions Of States: Designing A Scalable Moe Architecture With RWKV-7 Meta-learner'
authors: Liu Xiao, Li Zhiyuan, Lin Yueyu
conference: "Arxiv"
year: 2025
bibkey: xiao2025millions
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08247'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Training Techniques', 'Tools', 'GPT', 'Scaling Laws', 'Reinforcement Learning', 'Pretraining Methods']
---
State-based sequence models like RWKV-7 offer a compelling alternative to
Transformer architectures, achieving linear complexity while demonstrating
greater expressive power in short-context scenarios and enabling state tracking
beyond the \(\text\{TC\}^0\) complexity class. However, RWKV-7 lacks mechanisms
for token-parameter interactions and native scalability, limiting its
adaptability and growth without retraining. In this paper, we propose
\textbf\{Meta-State\}, a novel extension to RWKV-7 that replaces attention
mechanisms with a fully state-driven approach, integrating token-parameter
interactions through a \textbf\{Self-State Encoder\} (SSE) mechanism. The SSE
repurposes a portion of the RWKV-7 Weighted Key-Value (WKV) state as
transformation weights to encode token-parameter interactions in a linear,
state-driven manner without introducing new trainable matrices or softmax
operations, while preserving the autoregressive property of token processing.
Meta-State supports progressive model scaling by expanding the WKV state and
parameter tokens, reusing existing parameters without retraining. Our approach
bridges the gap between state-based modeling, token-parameter interactions, and
scalable architectures, offering a flexible framework for efficient and
adaptable sequence modeling with linear complexity and constant memory usage.
