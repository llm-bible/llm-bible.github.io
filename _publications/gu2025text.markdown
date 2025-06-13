---
layout: publication
title: 'Text Compression For Efficient Language Generation'
authors: David Gu, Peter Belcak, Roger Wattenhofer
conference: "Arxiv"
year: 2025
bibkey: gu2025text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11426"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'Applications', 'Language Modeling', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods']
---
We challenge the prevailing assumption that LLMs must rely fully on sub-word
tokens for high-quality text generation. To this end, we propose the
"Generative Pretrained Thoughtformer" (GPTHF), a hierarchical transformer
language model capable of text generation by compressing text into sentence
embeddings and employing a sentence attention mechanism. GPTHF retains GPT's
architecture, modifying only token interactions via dynamic sparse attention
masks.
  Our experiments show that GPTHF achieves an up to an order of magnitude
improvement in FLOPs efficiency and a threefold increase in runtime speed
compared to equally-sized GPT models in the low-size regime. This is achieved
through a unique generation method that caches and reuses sentence embeddings,
allowing significant portions of the input to bypass large parts of the
network.
