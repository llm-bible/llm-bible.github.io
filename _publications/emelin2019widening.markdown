---
layout: publication
title: 'Widening The Representation Bottleneck In Neural Machine Translation With Lexical Shortcuts'
authors: Denis Emelin, Ivan Titov, Rico Sennrich
conference: "Arxiv"
year: 2019
bibkey: emelin2019widening
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1906.12284"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'WMT', 'Attention Mechanism', 'Pretraining Methods']
---
The transformer is a state-of-the-art neural translation model that uses
attention to iteratively refine lexical representations with information drawn
from the surrounding context. Lexical features are fed into the first layer and
propagated through a deep network of hidden layers. We argue that the need to
represent and propagate lexical features in each layer limits the model's
capacity for learning and representing other information relevant to the task.
To alleviate this bottleneck, we introduce gated shortcut connections between
the embedding layer and each subsequent layer within the encoder and decoder.
This enables the model to access relevant lexical content dynamically, without
expending limited resources on storing it within intermediate states. We show
that the proposed modification yields consistent improvements over a baseline
transformer on standard WMT translation tasks in 5 translation directions (0.9
BLEU on average) and reduces the amount of lexical information passed along the
hidden layers. We furthermore evaluate different ways to integrate lexical
connections into the transformer architecture and present ablation experiments
exploring the effect of proposed shortcuts on model behavior.
