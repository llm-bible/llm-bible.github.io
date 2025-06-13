---
layout: publication
title: 'Language Models "grok" To Copy'
authors: Ang Lv, Ruobing Xie, Xingwu Sun, Zhanhui Kang, Rui Yan
conference: "Arxiv"
year: 2024
bibkey: lv2024language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.09281'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Pre-Training', 'In-Context Learning', 'Pretraining Methods']
---
We examine the pre-training dynamics of language models, focusing on their
ability to copy text from preceding context--a fundamental skill for various
LLM applications, including in-context learning (ICL) and retrieval-augmented
generation (RAG). We propose a novel perspective that Transformer-based
language models develop copying abilities similarly to grokking, which refers
to sudden generalization on test set long after the model fit to the training
set. Our experiments yield three arguments: (1) The pre-training loss decreases
rapidly, while the context copying ability of models initially lags and then
abruptly saturates. (2) The speed of developing copying ability is independent
of the number of tokens trained, similarly to how grokking speed is unaffected
by dataset size as long as the data distribution is preserved. (3) Induction
heads, the attention heads responsible for copying, form from shallow to deep
layers during training, mirroring the development of circuits in deeper layers
during grokking. We contend that the connection between grokking and context
copying can provide valuable insights for more effective language model
training, ultimately improving in-context performance. For example, we
demonstrated that techniques that enhance grokking, such as regularization,
either accelerate or enhance the development of context copying.
