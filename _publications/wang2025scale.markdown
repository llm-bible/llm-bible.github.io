---
layout: publication
title: 'Scale-distribution Decoupling: Enabling Stable And Effective Training Of Large Language Models'
authors: Ya Wang, Zhijian Zhuo, Yutao Zeng, Xun Zhou, Jian Yang, Xiaoqing Li
conference: "Arxiv"
year: 2025
bibkey: wang2025scale
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15499'}
  - {name: "Code", url: 'https://github.com/kaihemo/SDD'}
tags: ['Has Code', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Training stability is a persistent challenge in the pre-training of large
language models (LLMs), particularly for architectures such as Post-Norm
Transformers, which are prone to gradient explosion and dissipation. In this
paper, we propose Scale-Distribution Decoupling (SDD), a novel approach that
stabilizes training by explicitly decoupling the scale and distribution of the
weight matrix in fully-connected layers. SDD applies a normalization mechanism
to regulate activations and a learnable scaling vector to maintain
well-conditioned gradients, effectively preventing \\(\textbf\{gradient explosion
and dissipation\}\\). This separation improves optimization efficiency,
particularly in deep networks, by ensuring stable gradient propagation.
Experimental results demonstrate that our method stabilizes training across
various LLM architectures and outperforms existing techniques in different
normalization configurations. Furthermore, the proposed method is lightweight
and compatible with existing frameworks, making it a practical solution for
stabilizing LLM training. Code is available at https://github.com/kaihemo/SDD.
