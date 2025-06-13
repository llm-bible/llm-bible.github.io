---
layout: publication
title: 'GAAMA 2.0: An Integrated System That Answers Boolean And Extractive Questions'
authors: Scott Mccarley, Mihaela Bornea, Sara Rosenthal, Anthony Ferritto, Md Arafat Sultan, Avirup Sil, Radu Florian
conference: "Arxiv"
year: 2022
bibkey: mccarley2022gaama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.08441"}
tags: ['Transformer', 'Pretraining Methods', 'Model Architecture', 'Reinforcement Learning']
---
Recent machine reading comprehension datasets include extractive and boolean
questions but current approaches do not offer integrated support for answering
both question types. We present a multilingual machine reading comprehension
system and front-end demo that handles boolean questions by providing both a
YES/NO answer and highlighting supporting evidence, and handles extractive
questions by highlighting the answer in the passage. Our system, GAAMA 2.0, is
ranked first on the Tydi QA leaderboard at the time of this writing. We
contrast two different implementations of our approach. The first includes
several independent stacks of transformers allowing easy deployment of each
component. The second is a single stack of transformers utilizing adapters to
reduce GPU memory footprint in a resource-constrained environment.
