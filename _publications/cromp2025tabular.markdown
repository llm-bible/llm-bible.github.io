---
layout: publication
title: 'Tabby: Tabular Data Synthesis With Language Models'
authors: Sonia Cromp, Satya Sai Srinath Namburi Gnvv, Mohammed Alkhudhayri, Catherine Cao, Samuel Guo, Nicholas Roberts, Frederic Sala
conference: "Arxiv"
year: 2025
bibkey: cromp2025tabular
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02152'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
While advances in large language models (LLMs) have greatly improved the
quality of synthetic text data in recent years, synthesizing tabular data has
received relatively less attention. We address this disparity with Tabby, a
simple but powerful post-training modification to the standard Transformer
language model architecture, enabling its use for tabular dataset synthesis.
Tabby enables the representation of differences across columns using Gated
Mixture-of-Experts, with column-specific sets of parameters. Empirically, Tabby
results in data quality near or equal to that of real data. By pairing our
novel LLM table training technique, Plain, with Tabby, we observe up to a 44%
improvement in quality over previous methods. We also show that Tabby extends
beyond tables to more general structured data, reaching parity with real data
on a nested JSON dataset as well.
