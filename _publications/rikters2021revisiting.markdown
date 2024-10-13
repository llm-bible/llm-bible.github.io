---
layout: publication
title: 'Revisiting Context Choices For Context-aware Machine Translation'
authors: Rikters Matīss, Nakazawa Toshiaki
conference: "Proceedings of the"
year: 2021
bibkey: rikters2021revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.02995"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
One of the most popular methods for context-aware machine translation (MT) is
to use separate encoders for the source sentence and context as multiple
sources for one target sentence. Recent work has cast doubt on whether these
models actually learn useful signals from the context or are improvements in
automatic evaluation metrics just a side-effect. We show that multi-source
transformer models improve MT over standard transformer-base models even with
empty lines provided as context, but the translation quality improves
significantly (1.51 - 2.65 BLEU) when a sufficient amount of correct context is
provided. We also show that even though randomly shuffling in-domain context
can also improve over baselines, the correct context further improves
translation quality and random out-of-domain context further degrades it.
