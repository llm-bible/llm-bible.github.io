---
layout: publication
title: Discovering Latent Knowledge In Language Models Without Supervision
authors: Collin Burns, Haotian Ye, Dan Klein, Jacob Steinhardt
conference: Arxiv
year: 2022
citations: 33
bibkey: burns2022discovering
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.03827'}]
tags: [RAG, Reinforcement Learning, Prompting]
---
Existing techniques for training language models can be misaligned with the
truth: if we train models with imitation learning, they may reproduce errors
that humans make; if we train them to generate text that humans rate highly,
they may output errors that human evaluators can't detect. We propose
circumventing this issue by directly finding latent knowledge inside the
internal activations of a language model in a purely unsupervised way.
Specifically, we introduce a method for accurately answering yes-no questions
given only unlabeled model activations. It works by finding a direction in
activation space that satisfies logical consistency properties, such as that a
statement and its negation have opposite truth values. We show that despite
using no supervision and no model outputs, our method can recover diverse
knowledge represented in large language models: across 6 models and 10
question-answering datasets, it outperforms zero-shot accuracy by 4% on
average. We also find that it cuts prompt sensitivity in half and continues to
maintain high accuracy even when models are prompted to generate incorrect
answers. Our results provide an initial step toward discovering what language
models know, distinct from what they say, even when we don't have access to
explicit ground truth labels.