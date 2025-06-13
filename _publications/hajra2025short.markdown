---
layout: publication
title: 'Short-range Dependency Effects On Transformer Instability And A Decomposed Attention Solution'
authors: Suvadeep Hajra
conference: "Arxiv"
year: 2025
bibkey: hajra2025short
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15548"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Transformer language models have driven significant progress across various fields, including natural language processing and computer vision. A central component of these models is the self-attention (SA) mechanism, which learns rich vector representations of tokens by modeling their relationships with others in a sequence. However, despite extensive research, transformers continue to suffer from training instability -- often manifesting as spikes or divergence in the training loss during a run.
  In this work, we identify one source of this instability: SA's limited ability to capture short-range dependencies, especially in tasks like language modeling, where almost every token heavily relies on its nearby neighbors. This limitation causes the pre-softmax logits of SA to grow rapidly, destabilizing training. To address this, we propose decomposing the SA into local (short-range) and global (long-range) attention heads. This decomposed attention, referred to as Long Short-attention (LS-attention), mitigates logit explosion and results in more stable training compared to an equivalent multi-head self-attention (MHSA). Empirical comparisons with two alternative training stabilization methods show that LS-attention reduces the validation perplexity to nearly 2/5 of that achieved by one method and reaches a similar perplexity as the other method using only 1/20 of the GPU hours. Additionally, our experiments demonstrate that LS-attention reduces inference latency by up to 36% compared to a state-of-the-art implementation of equivalent MHSA.
