---
layout: publication
title: 'CANINE: Pre-training An Efficient Tokenization-free Encoder For Language Representation'
authors: Clark Jonathan H., Garrette Dan, Turc Iulia, Wieting John
conference: "Transactions of the Association for Computational Linguistics"
year: 2021
bibkey: clark2021pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.06874"}
tags: ['BERT', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tokenization', 'Training Techniques', 'Transformer']
---
"Pipelined NLP systems have largely been superseded by end-to-end neural modeling, yet nearly all commonly-used models still require an explicit tokenization step. While recent tokenization approaches based on data-derived subword lexicons are less brittle than manually engineered tokenizers, these techniques are not equally suited to all languages, and the use of any fixed vocabulary may limit a model's ability to adapt. In this paper, we present CANINE, a neural encoder that operates directly on character sequences, without explicit tokenization or vocabulary, and a pre-training strategy that operates either directly on characters or optionally uses subwords as a soft inductive bias. To use its finer-grained input effectively and efficiently, CANINE combines downsampling, which reduces the input sequence length, with a deep transformer stack, which encodes context. CANINE outperforms a comparable mBERT model by 2.8 F1 on TyDi QA, a challenging multilingual benchmark, despite having 28&#37; fewer model parameters."
