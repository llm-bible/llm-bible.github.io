---
layout: publication
title: Toolformer Language Models Can Teach Themselves to Use Tools
authors: Schick Timo, Dwivedi-yu Jane, Dessì Roberto, Raileanu Roberta, Lomeli Maria, Zettlemoyer Luke, Cancedda Nicola, Scialom Thomas
conference: "Arxiv"
year: 2023
bibkey: schick2023toolformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.04761"}
tags: ['Language Modeling', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Language models (LMs) exhibit remarkable abilities to solve new tasks from just a few examples or textual instructions especially at scale. They also paradoxically struggle with basic functionality such as arithmetic or factual lookup where much simpler and smaller models excel. In this paper we show that LMs can teach themselves to use external tools via simple APIs and achieve the best of both worlds. We introduce Toolformer a model trained to decide which APIs to call when to call them what arguments to pass and how to best incorporate the results into future token prediction. This is done in a self-supervised way requiring nothing more than a handful of demonstrations for each API. We incorporate a range of tools including a calculator a QA system two different search engines a translation system and a calendar. Toolformer achieves substantially improved zero-shot performance across a variety of downstream tasks often competitive with much larger models without sacrificing its core language modeling abilities.
