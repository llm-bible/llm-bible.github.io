---
layout: publication
title: Answer Assemble Ace Understanding How Transformers Answer Multiple Choice Questions
authors: Wiegreffe Sarah, Tafjord Oyvind, Belinkov Yonatan, Hajishirzi Hannaneh, Sabharwal Ashish
conference: "Arxiv"
year: 2024
bibkey: wiegreffe2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15018"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Multiple-choice question answering (MCQA) is a key competence of performant transformer language models that is tested by mainstream benchmarks. However recent evidence shows that models can have quite a range of performance particularly when the task format is diversified slightly (such as by shuffling answer choice order). In this work we ask how do successful models perform formatted MCQA We employ vocabulary projection and activation patching methods to localize key hidden states that encode relevant information for predicting the correct answer. We find that prediction of a specific answer symbol is causally attributed to a single middle layer and specifically its multi-head self-attention mechanism. We show that subsequent layers increase the probability of the predicted answer symbol in vocabulary space and that this probability increase is associated with a sparse set of attention heads with unique roles. We additionally uncover differences in how different models adjust to alternative symbols. Finally we demonstrate that a synthetic task can disentangle sources of model error to pinpoint when a model has learned formatted MCQA and show that an inability to separate answer symbol tokens in vocabulary space is a property of models unable to perform formatted MCQA tasks.
