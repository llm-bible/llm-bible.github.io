---
layout: publication
title: 'Complexformer: Disruptively Advancing Transformer Inference Ability Via Head-specific Complex Vector Attention'
authors: Jintian Shao, Hongyi Huang, Jiayi Wu, Beiwen Zhang, Zhiyu Wu, You Shan, Mingkai Zheng
conference: "Arxiv"
year: 2025
bibkey: shao2025disruptively
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10222'}
tags: ['Attention Mechanism', 'Language Modeling', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Pretraining Methods']
---
Transformer models rely on self-attention to capture token dependencies but face challenges in effectively integrating positional information while allowing multi-head attention (MHA) flexibility. Prior methods often model semantic and positional differences disparately or apply uniform positional adjustments across heads, potentially limiting representational capacity. This paper introduces ComplexFormer, featuring Complex Multi-Head Attention-CMHA. CMHA empowers each head to independently model semantic and positional differences unified within the complex plane, representing interactions as rotations and scaling. ComplexFormer incorporates two key improvements: (1) a per-head Euler transformation, converting real-valued query/key projections into polar-form complex vectors for head-specific complex subspace operation; and (2) a per-head adaptive differential rotation mechanism, exp[i(Adapt(ASmn,i) + Delta(Pmn),i)], allowing each head to learn distinct strategies for integrating semantic angle differences (ASmn,i) with relative positional encodings (Delta(Pmn),i). Extensive experiments on language modeling, text generation, code generation, and mathematical reasoning show ComplexFormer achieves superior performance, significantly lower generation perplexity , and improved long-context coherence compared to strong baselines like RoPE-Transformers. ComplexFormer demonstrates strong parameter efficiency, offering a more expressive, adaptable attention mechanism.
