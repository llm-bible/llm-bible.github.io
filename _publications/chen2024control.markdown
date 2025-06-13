---
layout: publication
title: 'Control-dag: Constrained Decoding For Non-autoregressive Directed Acyclic T5 Using Weighted Finite State Automata'
authors: Jinghong Chen, Weizhe Lin, Jingbiao Mei, Bill Byrne
conference: "Arxiv"
year: 2024
bibkey: chen2024control
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06854"}
tags: ['Model Architecture', 'GPT', 'Pretraining Methods', 'Transformer', 'Applications']
---
The Directed Acyclic Transformer is a fast non-autoregressive (NAR) model
that performs well in Neural Machine Translation. Two issues prevent its
application to general Natural Language Generation (NLG) tasks: frequent
Out-Of-Vocabulary (OOV) errors and the inability to faithfully generate entity
names. We introduce Control-DAG, a constrained decoding algorithm for our
Directed Acyclic T5 (DA-T5) model which offers lexical, vocabulary and length
control. We show that Control-DAG significantly enhances DA-T5 on the Schema
Guided Dialogue and the DART datasets, establishing strong NAR results for
Task-Oriented Dialogue and Data-to-Text NLG.
