---
layout: publication
title: 'El-attention: Memory Efficient Lossless Attention For Generation'
authors: Yu Yan, Jiusheng Chen, Weizhen Qi, Nikhil Bhendawade, Yeyun Gong, Nan Duan, Ruofei Zhang
conference: "Arxiv"
year: 2021
bibkey: yan2021el
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2105.04779'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'GPT', 'Model Architecture', 'Applications', 'Pretraining Methods']
---
Transformer model with multi-head attention requires caching intermediate
results for efficient inference in generation tasks. However, cache brings new
memory-related costs and prevents leveraging larger batch size for faster
speed. We propose memory-efficient lossless attention (called EL-attention) to
address this issue. It avoids heavy operations for building multi-head keys and
values, cache for them is not needed. EL-attention constructs an ensemble of
attention results by expanding query while keeping key and value shared. It
produces the same result as multi-head attention with less GPU memory and
faster inference speed. We conduct extensive experiments on Transformer, BART,
and GPT-2 for summarization and question generation tasks. The results show
EL-attention speeds up existing models by 1.6x to 5.3x without accuracy loss.
