---
layout: publication
title: 'A Data Source For Reasoning Embodied Agents'
authors: Jack Lanchantin, Sainbayar Sukhbaatar, Gabriel Synnaeve, Yuxuan Sun, Kavya Srinet, Arthur Szlam
conference: "Arxiv"
year: 2023
bibkey: lanchantin2023data
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.07974'}
tags: ['Agentic', 'Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Recent progress in using machine learning models for reasoning tasks has been
driven by novel model architectures, large-scale pre-training protocols, and
dedicated reasoning datasets for fine-tuning. In this work, to further pursue
these advances, we introduce a new data generator for machine reasoning that
integrates with an embodied agent. The generated data consists of templated
text queries and answers, matched with world-states encoded into a database.
The world-states are a result of both world dynamics and the actions of the
agent. We show the results of several baseline models on instantiations of
train sets. These include pre-trained language models fine-tuned on a
text-formatted representation of the database, and graph-structured
Transformers operating on a knowledge-graph representation of the database. We
find that these models can answer some questions about the world-state, but
struggle with others. These results hint at new research directions in
designing neural reasoning models and database representations. Code to
generate the data will be released at github.com/facebookresearch/neuralmemory
