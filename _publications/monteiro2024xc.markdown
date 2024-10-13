---
layout: publication
title: 'Xc-cache: Cross-attending To Cached Context For Efficient LLM Inference'
authors: Monteiro João, Marcotte Étienne, Noël Pierre-andré, Zantedeschi Valentina, Vázquez David, Chapados Nicolas, Pal Christopher, Taslakian Perouz
conference: "Arxiv"
year: 2024
bibkey: monteiro2024xc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15420"}
tags: ['Attention Mechanism', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
In-context learning (ICL) approaches typically leverage prompting to
condition decoder-only language model generation on reference information.
Just-in-time processing of a context is inefficient due to the quadratic cost
of self-attention operations, and caching is desirable. However, caching
transformer states can easily require almost as much space as the model
parameters. When the right context isn't known in advance, caching ICL can be
challenging. This work addresses these limitations by introducing models that,
inspired by the encoder-decoder architecture, use cross-attention to condition
generation on reference text without the prompt. More precisely, we leverage
pre-trained decoder-only models and only train a small number of added layers.
We use Question-Answering (QA) as a testbed to evaluate the ability of our
models to perform conditional generation and observe that they outperform ICL,
are comparable to fine-tuned prompted LLMs, and drastically reduce the space
footprint relative to standard KV caching by two orders of magnitude.
