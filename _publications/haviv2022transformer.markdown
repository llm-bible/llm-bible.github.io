---
layout: publication
title: Transformer Language Models Without Positional Encodings Still Learn Positional Information
authors: Haviv Adi, Ram Ori, Press Ofir, Izsak Peter, Levy Omer
conference: "Arxiv"
year: 2022
bibkey: haviv2022transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.16634"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Causal transformer language models (LMs) such as GPT-3 typically require some form of positional encoding such as positional embeddings. However we show that LMs without any explicit positional encoding are still competitive with standard models and that this phenomenon is robust across different datasets model sizes and sequence lengths. Probing experiments reveal that such models acquire an implicit notion of absolute positions throughout the network effectively compensating for the missing information. We conjecture that causal attention enables the model to infer the number of predecessors that each token can attend to thereby approximating its absolute position. Our findings indicate that causal LMs might derive positional awareness not only from the explicit positioning mechanism but also from the effects of the causal mask.
