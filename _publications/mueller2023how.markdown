---
layout: publication
title: 'How To Plant Trees In Language Models: Data And Architectural Effects On The Emergence Of Syntactic Inductive Biases'
authors: Aaron Mueller, Tal Linzen
conference: "Arxiv"
year: 2023
bibkey: mueller2023how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19905"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Pre-Training']
---
Accurate syntactic representations are essential for robust generalization in
natural language. Recent work has found that pre-training can teach language
models to rely on hierarchical syntactic features - as opposed to incorrect
linear features - when performing tasks after fine-tuning. We test what aspects
of pre-training are important for endowing encoder-decoder Transformers with an
inductive bias that favors hierarchical syntactic generalizations. We focus on
architectural features (depth, width, and number of parameters), as well as the
genre and size of the pre-training corpus, diagnosing inductive biases using
two syntactic transformation tasks: question formation and passivization, both
in English. We find that the number of parameters alone does not explain
hierarchical generalization: model depth plays greater role than model width.
We also find that pre-training on simpler language, such as child-directed
speech, induces a hierarchical bias using an order-of-magnitude less data than
pre-training on more typical datasets based on web text or Wikipedia; this
suggests that in cognitively plausible language acquisition settings, neural
language models may be more data-efficient than previously thought.
