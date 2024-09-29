---
layout: publication
title: ∞45;former Infinite Memory Transformer
authors: Martins Pedro Henrique, Marinho Zita, Martins André F. T.
conference: "Arxiv"
year: 2021
bibkey: martins2021infinite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.00301"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Transformers are unable to model long45;term memories effectively since the amount of computation they need to perform grows with the context length. While variations of efficient transformers have been proposed they all have a finite memory capacity and are forced to drop old information. In this paper we propose the ∞45;former which extends the vanilla transformer with an unbounded long45;term memory. By making use of a continuous45;space attention mechanism to attend over the long45;term memory the ∞45;formers attention complexity becomes independent of the context length trading off memory length with precision. In order to control where precision is more important ∞45;former maintains sticky memories being able to model arbitrarily long contexts while keeping the computation budget fixed. Experiments on a synthetic sorting task language modeling and document grounded dialogue generation demonstrate the ∞45;formers ability to retain information from long sequences.
