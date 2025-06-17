---
layout: publication
title: 'Fastformer: Additive Attention Can Be All You Need'
authors: Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang, Xing Xie
conference: Arxiv
year: 2021
citations: 69
bibkey: wu2021additive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.09084'}]
tags: [Transformer, Attention Mechanism, Model Architecture]
---
Transformer is a powerful model for text understanding. However, it is
inefficient due to its quadratic complexity to input sequence length. Although
there are many methods on Transformer acceleration, they are still either
inefficient on long sequences or not effective enough. In this paper, we
propose Fastformer, which is an efficient Transformer model based on additive
attention. In Fastformer, instead of modeling the pair-wise interactions
between tokens, we first use additive attention mechanism to model global
contexts, and then further transform each token representation based on its
interaction with global context representations. In this way, Fastformer can
achieve effective context modeling with linear complexity. Extensive
experiments on five datasets show that Fastformer is much more efficient than
many existing Transformer models and can meanwhile achieve comparable or even
better long text modeling performance.