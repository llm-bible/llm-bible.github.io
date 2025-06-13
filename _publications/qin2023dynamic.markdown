---
layout: publication
title: 'Dodo: Dynamic Contextual Compression For Decoder-only Lms'
authors: Guanghui Qin, Corby Rosset, Ethan C. Chau, Nikhil Rao, Benjamin Van Durme
conference: "ACL 2024"
year: 2023
bibkey: qin2023dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02409"}
tags: ['Fine-Tuning', 'Transformer', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
Transformer-based language models (LMs) are inefficient in long contexts. We
propose Dodo, a solution for context compression. Instead of one vector per
token in a standard transformer model, Dodo represents text with a dynamic
number of hidden states at each layer, reducing the cost of self-attention to a
fraction of typical time and space. Moreover, off-the-shelf models such as
LLaMA can be adapted to Dodo by efficient parameter tuning methods such as
LoRA. In use, Dodo can act as either an autoregressive LM or a context
compressor for downstream tasks. We demonstrate through experiments in language
modeling, question answering, and summarization that Dodo retains capabilities
in these tasks, while drastically reducing the overhead during decoding. For
example, in the autoencoding task, Dodo shrinks context at a 20x compression
ratio with a BLEU score of 98% for reconstruction, achieving nearly lossless
encoding.
