---
layout: publication
title: 'Multimodal Mamba: Decoder-only Multimodal State Space Model Via Quadratic To Linear Distillation'
authors: Bencheng Liao, Hongyuan Tao, Qian Zhang, Tianheng Cheng, Yingyue Li, Haoran Yin, Wenyu Liu, Xinggang Wang
conference: "Arxiv"
year: 2025
bibkey: liao2025multimodal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13145'}
  - {name: "Code", url: 'https://github.com/hustvl/mmMamba'}
tags: ['Has Code', 'Transformer', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Tools', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent Multimodal Large Language Models (MLLMs) have achieved remarkable
performance but face deployment challenges due to their quadratic computational
complexity, growing Key-Value cache requirements, and reliance on separate
vision encoders. We propose mmMamba, a framework for developing
linear-complexity native multimodal state space models through progressive
distillation from existing MLLMs using moderate academic computational
resources. Our approach enables the direct conversion of trained decoder-only
MLLMs to linear-complexity architectures without requiring pre-trained
RNN-based LLM or vision encoders. We propose an seeding strategy to carve Mamba
from trained Transformer and a three-stage distillation recipe, which can
effectively transfer the knowledge from Transformer to Mamba while preserving
multimodal capabilities. Our method also supports flexible hybrid architectures
that combine Transformer and Mamba layers for customizable
efficiency-performance trade-offs. Distilled from the Transformer-based
decoder-only HoVLE, mmMamba-linear achieves competitive performance against
existing linear and quadratic-complexity VLMs, while mmMamba-hybrid further
improves performance significantly, approaching HoVLE's capabilities. At 103K
tokens, mmMamba-linear demonstrates 20.6\\(\times\\) speedup and 75.8% GPU memory
reduction compared to HoVLE, while mmMamba-hybrid achieves 13.5\\(\times\\) speedup
and 60.2% memory savings. Code and models are released at
https://github.com/hustvl/mmMamba
