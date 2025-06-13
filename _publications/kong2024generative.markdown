---
layout: publication
title: 'GOFA: A Generative One-for-all Model For Joint Graph Language Modeling'
authors: Lecheng Kong, Jiarui Feng, Hao Liu, Chengsong Huang, Jiaxin Huang, Yixin Chen, Muhan Zhang
conference: "Arxiv"
year: 2024
bibkey: kong2024generative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.09709'}
  - {name: "Code", url: 'https://github.com/JiaruiFeng/GOFA'}
tags: ['Has Code', 'Language Modeling', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Foundation models, such as Large Language Models (LLMs) or Large Vision
Models (LVMs), have emerged as one of the most powerful tools in the respective
fields. However, unlike text and image data, graph data do not have a
definitive structure, posing great challenges to developing a Graph Foundation
Model (GFM). For example, current attempts at designing general graph models
either transform graph data into a language format for LLM-based prediction or
still train a GNN model with LLM as an assistant. The former can handle
unlimited tasks, while the latter captures graph structure much better -- yet,
no existing work can achieve both simultaneously. In this paper, we identify
three key desirable properties of a GFM: self-supervised pretraining, fluidity
in tasks, and graph awareness. To account for these properties, we extend the
conventional language modeling to the graph domain and propose a novel
generative graph language model GOFA to solve the problem. The model
interleaves randomly initialized GNN layers into a frozen pre-trained LLM so
that the semantic and structural modeling abilities are organically combined.
GOFA is pre-trained on newly proposed graph-level next-word prediction,
question-answering, and structural tasks to obtain the above GFM properties.
The pre-trained model is further fine-tuned on downstream tasks to obtain
task-solving ability. The fine-tuned model is evaluated on various downstream
tasks, demonstrating a strong ability to solve structural and contextual
problems in zero-shot scenarios. The code is available at
https://github.com/JiaruiFeng/GOFA.
