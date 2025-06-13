---
layout: publication
title: 'Provable Benefits Of Task-specific Prompts For In-context Learning'
authors: Xiangyu Chang, Yingcong Li, Muti Kara, Samet Oymak, Amit K. Roy-chowdhury
conference: "Arxiv"
year: 2025
bibkey: chang2025provable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02102'}
tags: ['Attention Mechanism', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
The in-context learning capabilities of modern language models have motivated
a deeper mathematical understanding of sequence models. A line of recent work
has shown that linear attention models can emulate projected gradient descent
iterations to implicitly learn the task vector from the data provided in the
context window. In this work, we consider a novel setting where the global task
distribution can be partitioned into a union of conditional task distributions.
We then examine the use of task-specific prompts and prediction heads for
learning the prior information associated with the conditional task
distribution using a one-layer attention model. Our results on loss landscape
show that task-specific prompts facilitate a covariance-mean decoupling where
prompt-tuning explains the conditional mean of the distribution whereas the
variance is learned/explained through in-context learning. Incorporating
task-specific head further aids this process by entirely decoupling estimation
of mean and variance components. This covariance-mean perspective similarly
explains how jointly training prompt and attention weights can provably help
over fine-tuning after pretraining.
