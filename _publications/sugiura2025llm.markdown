---
layout: publication
title: 'Llm-jp-modernbert: A Modernbert Model Trained On A Large-scale Japanese Corpus With Long Context Length'
authors: Issa Sugiura, Kouta Nakayama, Yusuke Oda
conference: "Arxiv"
year: 2025
bibkey: sugiura2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15544"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'BERT', 'Transformer']
---
Encoder-only transformer models like BERT are widely adopted as a pre-trained
backbone for tasks like sentence classification and retrieval. However,
pretraining of encoder models with large-scale corpora and long contexts has
been relatively underexplored compared to decoder-only transformers. In this
work, we present llm-jp-modernbert, a ModernBERT model trained on a publicly
available, massive Japanese corpus with a context length of 8192 tokens. While
our model does not surpass existing baselines on downstream tasks, it achieves
good results on fill-mask test evaluations. We also analyze the effect of
context length expansion through pseudo-perplexity experiments. Furthermore, we
investigate sentence embeddings in detail, analyzing their transitions during
training and comparing them with those from other existing models, confirming
similar trends with models sharing the same architecture. To support
reproducibility and foster the development of long-context BERT, we release our
model, along with the training and evaluation code.
