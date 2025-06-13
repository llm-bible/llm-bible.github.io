---
layout: publication
title: 'The Sharpness Disparity Principle In Transformers For Accelerating Language Model Pre-training'
authors: Jinbo Wang, Mingze Wang, Zhanpeng Zhou, Junchi Yan, Weinan E, Lei Wu
conference: "Arxiv"
year: 2025
bibkey: wang2025sharpness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19002'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Training Techniques', 'GPT', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Transformers consist of diverse building blocks, such as embedding layers,
normalization layers, self-attention mechanisms, and point-wise feedforward
networks. Thus, understanding the differences and interactions among these
blocks is important. In this paper, we uncover a clear Sharpness Disparity
across these blocks, which emerges early in training and intriguingly persists
throughout the training process. Motivated by this finding, we propose
Blockwise Learning Rate (LR), a strategy that tailors the LR to each block's
sharpness, accelerating large language model (LLM) pre-training. By integrating
Blockwise LR into AdamW, we consistently achieve lower terminal loss and nearly
\\(2\times\\) speedup compared to vanilla AdamW. We demonstrate this acceleration
across GPT-2 and LLaMA, with model sizes ranging from 0.12B to 1.1B and
datasets of OpenWebText and MiniPile. Finally, we incorporate Blockwise LR into
Adam-mini (Zhang et al., 2024), a recently proposed memory-efficient variant of
Adam, achieving a combined \\(2\times\\) speedup and \\(2\times\\) memory saving. These
results underscore the potential of exploiting the sharpness disparity to
improve LLM training.
