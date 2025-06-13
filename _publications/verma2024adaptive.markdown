---
layout: publication
title: 'Adaptive Large Language Models By Layerwise Attention Shortcuts'
authors: Prateek Verma, Mert Pilanci
conference: "Arxiv"
year: 2024
bibkey: verma2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.10870"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods']
---
Transformer architectures are the backbone of the modern AI revolution.
However, they are based on simply stacking the same blocks in dozens of layers
and processing information sequentially from one block to another. In this
paper, we propose to challenge this and introduce adaptive computations for
LLM-like setups, which allow the final layer to attend to all of the
intermediate layers as it deems fit through the attention mechanism, thereby
introducing computational \textbf\{attention shortcuts\}. These shortcuts can
thus make the architecture depth and context adaptive. We showcase four
different datasets, namely acoustic tokens, natural language, and symbolic
music, and we achieve superior performance for GPT-like architecture. We give
evidence via attention maps that the models learn complex dependencies across
layers that are adaptive in context and depth depending on the input tokens.
