---
layout: publication
title: 'Multitok: Variable-length Tokenization For Efficient Llms Adapted From LZW Compression'
authors: Noel Elias, Homa Esfahanizadeh, Kaan Kale, Sriram Vishwanath, Muriel Medard
conference: "Arxiv"
year: 2024
bibkey: elias2024variable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21548'}
tags: ['Training Techniques', 'Model Architecture', 'BERT', 'GPT', 'Tokenization']
---
Large language models have drastically changed the prospects of AI by
introducing technologies for more complex natural language processing. However,
current methodologies to train such LLMs require extensive resources including
but not limited to large amounts of data, expensive machinery, and lengthy
training. To solve this problem, this paper proposes a new tokenization method
inspired by universal Lempel-Ziv-Welch data compression that compresses
repetitive phrases into multi-word tokens. With MultiTok as a new tokenizing
tool, we show that language models are able to be trained notably more
efficiently while offering a similar accuracy on more succinct and compressed
training data. In fact, our results demonstrate that MultiTok achieves a
comparable performance to the BERT and GPT-2 standards as both a stand-alone
tokenizer and an add-on to existing tokenizers while also providing close to
2.5x faster training with more than 30% less training data.
