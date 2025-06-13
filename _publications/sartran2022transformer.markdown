---
layout: publication
title: 'Transformer Grammars: Augmenting Transformer Language Models With Syntactic Inductive Biases At Scale'
authors: Laurent Sartran, Samuel Barrett, Adhiguna Kuncoro, Miloš Stanojević, Phil Blunsom, Chris Dyer
conference: "Arxiv"
year: 2022
bibkey: sartran2022transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.00633"}
tags: ['Model Architecture', 'Language Modeling', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
We introduce Transformer Grammars (TGs), a novel class of Transformer
language models that combine (i) the expressive power, scalability, and strong
performance of Transformers and (ii) recursive syntactic compositions, which
here are implemented through a special attention mask and deterministic
transformation of the linearized tree. We find that TGs outperform various
strong baselines on sentence-level language modeling perplexity, as well as on
multiple syntax-sensitive language modeling evaluation metrics. Additionally,
we find that the recursive syntactic composition bottleneck which represents
each sentence as a single vector harms perplexity on document-level language
modeling, providing evidence that a different kind of memory mechanism -- one
that is independent of composed syntactic representations -- plays an important
role in current successful models of long text.
