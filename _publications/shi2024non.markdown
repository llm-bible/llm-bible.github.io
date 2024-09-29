---
layout: publication
title: Non45;autoregressive Sequence45;to45;sequence Vision45;language Models
authors: Shi Kunyu, Dong Qi, Goncalves Luis, Tu Zhuowen, Soatto Stefano
conference: "Arxiv"
year: 2024
bibkey: shi2024non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02249"}
tags: ['GPT', 'Language Modeling', 'Pretraining Methods']
---
Sequence45;to45;sequence vision45;language models are showing promise but their applicability is limited by their inference latency due to their autoregressive way of generating predictions. We propose a parallel decoding sequence45;to45;sequence vision45;language model trained with a Query45;CTC loss that marginalizes over multiple inference paths in the decoder. This allows us to model the joint distribution of tokens rather than restricting to conditional distribution as in an autoregressive model. The resulting model NARVL achieves performance on45;par with its state45;of45;the45;art autoregressive counterpart but is faster at inference time reducing from the linear complexity associated with the sequential generation of tokens to a paradigm of constant time joint inference.
