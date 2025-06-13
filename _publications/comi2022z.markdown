---
layout: publication
title: 'Z-BERT-A: A Zero-shot Pipeline For Unknown Intent Detection'
authors: Daniele Comi, Dimitrios Christofidellis, Pier Francesco Piazza, Matteo Manica
conference: "Arxiv"
year: 2022
bibkey: comi2022z
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.07084"}
  - {name: "Code", url: "https://github.com/GT4SD/zero-shot-bert-adapters"}
tags: ['Fine-Tuning', 'Transformer', 'Applications', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'BERT']
---
Intent discovery is a crucial task in natural language processing, and it is
increasingly relevant for various of industrial applications. Identifying
novel, unseen intents from user inputs remains one of the biggest challenges in
this field. Herein, we propose Zero-Shot-BERT-Adapters, a two-stage method for
multilingual intent discovery relying on a Transformer architecture, fine-tuned
with Adapters. We train the model for Natural Language Inference (NLI) and
later perform unknown intent classification in a zero-shot setting for multiple
languages. In our evaluation, we first analyze the quality of the model after
adaptive fine-tuning on known classes. Secondly, we evaluate its performance in
casting intent classification as an NLI task. Lastly, we test the zero-shot
performance of the model on unseen classes, showing how Zero-Shot-BERT-Adapters
can effectively perform intent discovery by generating semantically similar
intents, if not equal, to the ground-truth ones. Our experiments show how
Zero-Shot-BERT-Adapters outperforms various baselines in two zero-shot
settings: known intent classification and unseen intent discovery. The proposed
pipeline holds the potential for broad application in customer care. It enables
automated dynamic triage using a lightweight model that can be easily deployed
and scaled in various business scenarios, unlike large language models.
Zero-Shot-BERT-Adapters represents an innovative multi-language approach for
intent discovery, enabling the online generation of novel intents. A Python
package implementing the pipeline and the new datasets we compiled are
available at the following link:
https://github.com/GT4SD/zero-shot-bert-adapters.
