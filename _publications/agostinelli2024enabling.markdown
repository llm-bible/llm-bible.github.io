---
layout: publication
title: Leapformer Enabling Linear Transformers For Autoregressive And Simultaneous Tasks Via Learned Proportions
authors: Agostinelli Victor, Hong Sanghyun, Chen Lizhong
conference: "Arxiv"
year: 2024
bibkey: agostinelli2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13046"}
tags: ['Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
A promising approach to preserving model performance in linearized transformers is to employ position45;based re45;weighting functions. However state45;of45;the45;art re45;weighting functions rely heavily on target sequence lengths making it difficult or impossible to apply them to autoregressive and simultaneous tasks where the target and sometimes even the input sequence length are unknown. To address this issue we propose Learned Proportions (LeaP) and LeaPformers. Our contribution is built on two major components. First we generalize the dependence on explicit positional representations and sequence lengths into dependence on sequence proportions for re45;weighting. Second we replace static positional representations with dynamic proportions derived via a compact module enabling more flexible attention concentration patterns. We evaluate LeaPformer against eight representative efficient transformers on the Long45;Range Arena benchmark showing that LeaPformer achieves the best quality45;throughput trade45;off as well as LeaPformer to Wikitext45;103 autoregressive language modeling and simultaneous speech45;to45;text translation for two language pairs achieving competitive results.
