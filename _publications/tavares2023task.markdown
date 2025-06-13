---
layout: publication
title: 'Task Conditioned BERT For Joint Intent Detection And Slot-filling'
authors: Diogo Tavares, Pedro Azevedo, David Semedo, Ricardo Sousa, João Magalhães
conference: "Arxiv"
year: 2023
bibkey: tavares2023task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.06165"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'BERT', 'Transformer', 'Applications']
---
Dialogue systems need to deal with the unpredictability of user intents to
track dialogue state and the heterogeneity of slots to understand user
preferences. In this paper we investigate the hypothesis that solving these
challenges as one unified model will allow the transfer of parameter support
data across the different tasks. The proposed principled model is based on a
Transformer encoder, trained on multiple tasks, and leveraged by a rich input
that conditions the model on the target inferences. Conditioning the
Transformer encoder on multiple target inferences over the same corpus, i.e.,
intent and multiple slot types, allows learning richer language interactions
than a single-task model would be able to. In fact, experimental results
demonstrate that conditioning the model on an increasing number of dialogue
inference tasks leads to improved results: on the MultiWOZ dataset, the joint
intent and slot detection can be improved by 3.2% by conditioning on intent,
10.8% by conditioning on slot and 14.4% by conditioning on both intent and
slots. Moreover, on real conversations with Farfetch costumers, the proposed
conditioned BERT can achieve high joint-goal and intent detection performance
throughout a dialogue.
