---
layout: publication
title: Megalodon Efficient LLM Pretraining and Inference with Unlimited Context Length
authors: Ma Xuezhe, Yang Xiaomeng, Xiong Wenhan, Chen Beidi, Yu Lili, Zhang Hao, May Jonathan, Zettlemoyer Luke, Levy Omer, Zhou Chunting
conference: "Arxiv"
year: 2024
bibkey: ma2024megalodon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08801"}
  - {name: "Code", url: "https://github.com/XuezheMax/megalodon"}
tags: ['Transformer', 'Arxiv', 'LLM', 'Has Code', 'Attention Mechanism', 'Pretraining Methods']
---
The quadratic complexity and weak length extrapolation of Transformers limits their ability to scale to long sequences and while sub-quadratic solutions like linear attention and state space models exist they empirically underperform Transformers in pretraining efficiency and downstream task accuracy. We introduce Megalodon a neural architecture for efficient sequence modeling with unlimited context length. Megalodon inherits the architecture of Mega (exponential moving average with gated attention) and further introduces multiple technical components to improve its capability and stability including complex exponential moving average (CEMA) timestep normalization layer normalized attention mechanism and pre-norm with two-hop residual configuration. In a controlled head-to-head comparison with Llama2 Megalodon achieves better efficiency than Transformer in the scale of 7 billion parameters and 2 trillion training tokens. Megalodon reaches a training loss of 1.70 landing mid-way between Llama2-7B (1.75) and 13B (1.67). Code https://github.com/XuezheMax/megalodon
