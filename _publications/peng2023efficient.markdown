---
layout: publication
title: 'Yarn: Efficient Context Window Extension Of Large Language Models'
authors: Bowen Peng, Jeffrey Quesnelle, Honglu Fan, Enrico Shippole
conference: "Arxiv"
year: 2023
bibkey: peng2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.00071"}
  - {name: "Code", url: "https://github.com/jquesnelle/yarn"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Rotary Position Embeddings (RoPE) have been shown to effectively encode
positional information in transformer-based language models. However, these
models fail to generalize past the sequence length they were trained on. We
present YaRN (Yet another RoPE extensioN method), a compute-efficient method to
extend the context window of such models, requiring 10x less tokens and 2.5x
less training steps than previous methods. Using YaRN, we show that LLaMA
models can effectively utilize and extrapolate to context lengths much longer
than their original pre-training would allow, while also surpassing previous
the state-of-the-art at context window extension. In addition, we demonstrate
that YaRN exhibits the capability to extrapolate beyond the limited context of
a fine-tuning dataset. The models fine-tuned using YaRN has been made available
and reproduced online up to 128k context length at
https://github.com/jquesnelle/yarn
