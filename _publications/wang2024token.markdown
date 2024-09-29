---
layout: publication
title: Mambabyte: Token-free Selective State Space Model
authors: Wang Junxiong, Gangavarapu Tushaar, Yan Jing Nathan, Rush Alexander M.
conference: "Arxiv"
year: 2024
bibkey: wang2024token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13660"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Tokenization', 'Transformer']
---
Token-free language models learn directly from raw bytes and remove the inductive bias of subword tokenization. Operating on bytes however results in significantly longer sequences. In this setting standard autoregressive Transformers scale poorly as the effective memory required grows with sequence length. The recent development of the Mamba state space model (SSM) offers an appealing alternative approach with a fixed-sized memory state and efficient decoding. We propose MambaByte a token-free adaptation of the Mamba SSM trained autoregressively on byte sequences. In terms of modeling we show MambaByte to be competitive with and even to outperform state-of-the-art subword Transformers on language modeling tasks while maintaining the benefits of token-free language models such as robustness to noise. In terms of efficiency we develop an adaptation of speculative decoding with tokenized drafting and byte-level verification. This results in a 2.6(times) inference speedup to the standard MambaByte implementation showing similar decoding efficiency as the subword Mamba. These findings establish the viability of SSMs in enabling token-free language modeling.
