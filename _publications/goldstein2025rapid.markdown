---
layout: publication
title: 'RADLADS: Rapid Attention Distillation To Linear Attention Decoders At Scale'
authors: Daniel Goldstein, Eric Alcaide, Janna Lu, Eugene Cheah
conference: "Arxiv"
year: 2025
bibkey: goldstein2025rapid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03005"}
  - {name: "Code", url: "https://huggingface.co/collections/recursal/radlads-6818ee69e99e729ba8a87102"}
  - {name: "Code", url: "https://github.com/recursal/RADLADS-paper"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Distillation', 'Pretraining Methods', 'Transformer', 'Has Code', 'Attention Mechanism']
---
We present Rapid Attention Distillation to Linear Attention Decoders at Scale
(RADLADS), a protocol for rapidly converting softmax attention transformers
into linear attention decoder models, along with two new RWKV-variant
architectures, and models converted from popular Qwen2.5 open source models in
7B, 32B, and 72B sizes. Our conversion process requires only 350-700M tokens,
less than 0.005% of the token count used to train the original teacher models.
Converting to our 72B linear attention model costs less than \$2,000 USD at
today's prices, yet quality at inference remains close to the original
transformer. These models achieve state-of-the-art downstream performance
across a set of standard benchmarks for linear attention models of their size.
We release all our models on HuggingFace under the Apache 2.0 license, with the
exception of our 72B models which are also governed by the Qwen License
Agreement.
  Models at
https://huggingface.co/collections/recursal/radlads-6818ee69e99e729ba8a87102
Training Code at https://github.com/recursal/RADLADS-paper
