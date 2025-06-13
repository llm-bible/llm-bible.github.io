---
layout: publication
title: 'More Expressive Attention With Negative Weights'
authors: Ang Lv, Ruobing Xie, Shuaipeng Li, Jiayi Liao, Xingwu Sun, Zhanhui Kang, Di Wang, Rui Yan
conference: "Arxiv"
year: 2024
bibkey: lv2024more
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.07176"}
tags: ['Transformer', 'Model Architecture', 'Merging', 'Language Modeling', 'Reinforcement Learning', 'Security', 'Attention Mechanism', 'Pretraining Methods']
---
We propose a novel attention mechanism, named Cog Attention, that enables
attention weights to be negative for enhanced expressiveness, which stems from
two key factors: (1) Cog Attention enhances parameter flexibility. For example,
unlike traditional softmax attention heads that use a static output-value (OV)
matrix to delete or copy inputs that the heads attend to, Cog Attention
naturally learns to use the sign of dynamic query-key (QK) inner products to
represent these operations. This enables Cog Attention to perform multiple
operations simultaneously within a single head. Meanwhile, Cog Attention's OV
matrix can focus more on refinement or modification. (2) Cog Attention enhances
the model's robustness against representational collapse by preventing the
``over-squashing'' of earlier tokens into later positions. We develop
Transformer-like models which use Cog Attention as attention modules, including
decoder-only models at various scales for language modeling and U-ViT diffusion
models for image generation. Experiments show that models using Cog Attention
exhibit superior performance compared to those employing traditional softmax
attention modules. Our approach suggests a promising research direction for
rethinking and breaking the entrenched constraints of traditional softmax
attention, such as the requirement for non-negative weights.
