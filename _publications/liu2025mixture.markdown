---
layout: publication
title: 'Molae: Mixture Of Latent Experts For Parameter-efficient Language Models'
authors: Zehua Liu, Han Wu, Ruifeng She, Xiaojin Fu, Xiongwei Han, Tao Zhong, Mingxuan Yuan
conference: "Arxiv"
year: 2025
bibkey: liu2025mixture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23100'}
tags: ['Large-Scale Training', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Mixture of Experts (MoE) has become a key architectural paradigm for efficiently scaling Large Language Models (LLMs) by selectively activating a subset of parameters for each input token. However, standard MoE architectures face significant challenges, including high memory consumption and communication overhead during distributed training. In this paper, we introduce Mixture of Latent Experts (MoLAE), a novel parameterization that addresses these limitations by reformulating expert operations through a shared projection into a lower-dimensional latent space, followed by expert-specific transformations. This factorized approach substantially reduces parameter count and computational requirements, particularly in existing LLMs where hidden dimensions significantly exceed MoE intermediate dimensions. We provide a rigorous mathematical framework for transforming pre-trained MoE models into MoLAE architecture, characterizing conditions for optimal factorization, and developing a systematic two-step algorithm for this conversion. Our comprehensive theoretical analysis demonstrates that MoLAE significantly improves efficiency across multiple dimensions while preserving model capabilities. Experimental results confirm that MoLAE achieves comparable performance to standard MoE with substantially reduced resource requirements.
