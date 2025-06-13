---
layout: publication
title: 'Rethinking Homogeneity Of Vision And Text Tokens In Large Vision-and-language Models'
authors: Chia-wen Kuo, Sijie Zhu, Fan Chen, Xiaohui Shen, Longyin Wen
conference: "Arxiv"
year: 2025
bibkey: kuo2025rethinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01906'}
tags: ['Attention Mechanism', 'Ethics and Bias', 'Transformer', 'Model Architecture']
---
Large vision-and-language models (LVLMs) typically treat visual and textual
embeddings as homogeneous inputs to a large language model (LLM). However,
these inputs are inherently different: visual inputs are multi-dimensional and
contextually rich, often pre-encoded by models like CLIP, while textual inputs
lack this structure. In this paper, we propose Decomposed Attention (D-Attn), a
novel method that processes visual and textual embeddings differently by
decomposing the 1-D causal self-attention in LVLMs. After the attention
decomposition, D-Attn diagonalizes visual-to-visual self-attention, reducing
computation from \\(\mathcal\{O\}(|V|^2)\\) to \\(\mathcal\{O\}(|V|)\\) for \\(|V|\\) visual
embeddings without compromising performance. Moreover, D-Attn debiases
positional encodings in textual-to-visual cross-attention, further enhancing
visual understanding. Finally, we introduce an \\(\alpha\\)-weighting strategy to
merge visual and textual information, maximally preserving the pre-trained
LLM's capabilities with minimal modifications. Extensive experiments and
rigorous analyses validate the effectiveness of D-Attn, demonstrating
significant improvements on multiple image benchmarks while significantly
reducing computational costs. Code, data, and models will be publicly
available.
