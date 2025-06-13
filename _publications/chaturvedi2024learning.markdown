---
layout: publication
title: 'Learning Semantic Structure Through First-order-logic Translation'
authors: Akshay Chaturvedi, Nicholas Asher
conference: "Arxiv"
year: 2024
bibkey: chaturvedi2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03203"}
tags: ['Model Architecture', 'Pretraining Methods', 'BERT', 'Transformer', 'Prompting', 'Applications']
---
In this paper, we study whether transformer-based language models can extract
predicate argument structure from simple sentences. We firstly show that
language models sometimes confuse which predicates apply to which objects. To
mitigate this, we explore two tasks: question answering (Q/A), and first order
logic (FOL) translation, and two regimes, prompting and finetuning. In FOL
translation, we finetune several large language models on synthetic datasets
designed to gauge their generalization abilities. For Q/A, we finetune encoder
models like BERT and RoBERTa and use prompting for LLMs. The results show that
FOL translation for LLMs is better suited to learn predicate argument
structure.
