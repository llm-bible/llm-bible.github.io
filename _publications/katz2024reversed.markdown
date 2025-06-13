---
layout: publication
title: 'Reversed Attention: On The Gradient Descent Of Attention Layers In GPT'
authors: Shahar Katz, Lior Wolf
conference: "Arxiv"
year: 2024
bibkey: katz2024reversed
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.17019'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Reinforcement Learning', 'Interpretability', 'Pretraining Methods']
---
The success of Transformer-based Language Models (LMs) stems from their
attention mechanism. While this mechanism has been extensively studied in
explainability research, particularly through the attention values obtained
during the forward pass of LMs, the backward pass of attention has been largely
overlooked. In this work, we study the mathematics of the backward pass of
attention, revealing that it implicitly calculates an attention matrix we refer
to as "Reversed Attention". We examine the properties of Reversed Attention and
demonstrate its ability to elucidate the models' behavior and edit dynamics. In
an experimental setup, we showcase the ability of Reversed Attention to
directly alter the forward pass of attention, without modifying the model's
weights, using a novel method called "attention patching". In addition to
enhancing the comprehension of how LM configure attention layers during
backpropagation, Reversed Attention maps contribute to a more interpretable
backward pass.
