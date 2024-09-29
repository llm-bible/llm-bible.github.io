---
layout: publication
title: How Effective Are State Space Models For Machine Translation
authors: Pitorro Hugo, Vasylenko Pavlo, Treviso Marcos, Martins André F. T.
conference: "Arxiv"
year: 2024
bibkey: pitorro2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05489"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques', 'Transformer']
---
Transformers are the current architecture of choice for NLP but their attention layers do not scale well to long contexts. Recent works propose to replace attention with linear recurrent layers 45;45; this is the case for state space models which enjoy efficient training and inference. However it remains unclear whether these models are competitive with transformers in machine translation (MT). In this paper we provide a rigorous and comprehensive experimental comparison between transformers and linear recurrent models for MT. Concretely we experiment with RetNet Mamba and hybrid versions of Mamba which incorporate attention mechanisms. Our findings demonstrate that Mamba is highly competitive with transformers on sentence and paragraph45;level datasets where in the latter both models benefit from shifting the training distribution towards longer sequences. Further analysis show that integrating attention into Mamba improves translation quality robustness to sequence length extrapolation and the ability to recall named entities.
