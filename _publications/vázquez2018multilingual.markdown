---
layout: publication
title: 'Multilingual NMT With A Language-independent Attention Bridge'
authors: Raúl Vázquez, Alessandro Raganato, Jörg Tiedemann, Mathias Creutz
conference: "Proceedings of the 4th Workshop on Representation Learning for NLP (RepL4NLP-2019) Pages 33-39"
year: 2018
bibkey: vázquez2018multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1811.00498"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Transformer', 'Fine-Tuning', 'Attention Mechanism']
---
In this paper, we propose a multilingual encoder-decoder architecture capable
of obtaining multilingual sentence representations by means of incorporating an
intermediate \{\em attention bridge\} that is shared across all languages. That
is, we train the model with language-specific encoders and decoders that are
connected via self-attention with a shared layer that we call attention bridge.
This layer exploits the semantics from each language for performing translation
and develops into a language-independent meaning representation that can
efficiently be used for transfer learning. We present a new framework for the
efficient development of multilingual NMT using this model and scheduled
training. We have tested the approach in a systematic way with a multi-parallel
data set. We show that the model achieves substantial improvements over strong
bilingual models and that it also works well for zero-shot translation, which
demonstrates its ability of abstraction and transfer learning.
