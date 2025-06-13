---
layout: publication
title: 'Weight-based Analysis Of Detokenization In Language Models: Understanding The First Stage Of Inference Without Inference'
authors: Go Kamoda, Benjamin Heinzerling, Tatsuro Inaba, Keito Kudo, Keisuke Sakaguchi, Kentaro Inui
conference: "Arxiv"
year: 2025
bibkey: kamoda2025weight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15754"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Tokenization', 'GPT', 'Ethics and Bias', 'Interpretability and Explainability', 'Attention Mechanism']
---
According to the stages-of-inference hypothesis, early layers of language
models map their subword-tokenized input, which does not necessarily correspond
to a linguistically meaningful segmentation, to more meaningful representations
that form the model's "inner vocabulary". Prior analysis of this detokenization
stage has predominantly relied on probing and interventions such as path
patching, which involve selecting particular inputs, choosing a subset of
components that will be patched, and then observing changes in model behavior.
Here, we show that several important aspects of the detokenization stage can be
understood purely by analyzing model weights, without performing any model
inference steps. Specifically, we introduce an analytical decomposition of
first-layer attention in GPT-2. Our decomposition yields interpretable terms
that quantify the relative contributions of position-related, token-related,
and mixed effects. By focusing on terms in this decomposition, we discover
weight-based explanations of attention bias toward close tokens and attention
for detokenization.
