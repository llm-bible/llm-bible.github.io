---
layout: publication
title: Multilingual NMT With A Language45;independent Attention Bridge
authors: Vázquez Raúl, Raganato Alessandro, Tiedemann Jörg, Creutz Mathias
conference: "Proceedings of the"
year: 2018
bibkey: vázquez2018multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1811.00498"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Tools', 'Training Techniques']
---
In this paper we propose a multilingual encoder45;decoder architecture capable of obtaining multilingual sentence representations by means of incorporating an intermediate 123;em attention bridge125; that is shared across all languages. That is we train the model with language45;specific encoders and decoders that are connected via self45;attention with a shared layer that we call attention bridge. This layer exploits the semantics from each language for performing translation and develops into a language45;independent meaning representation that can efficiently be used for transfer learning. We present a new framework for the efficient development of multilingual NMT using this model and scheduled training. We have tested the approach in a systematic way with a multi45;parallel data set. We show that the model achieves substantial improvements over strong bilingual models and that it also works well for zero45;shot translation which demonstrates its ability of abstraction and transfer learning.
