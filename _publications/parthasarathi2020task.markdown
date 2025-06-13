---
layout: publication
title: 'On Task-level Dialogue Composition Of Generative Transformer Model'
authors: Prasanna Parthasarathi, Arvind Neelakantan, Sharan Narang
conference: "Arxiv"
year: 2020
bibkey: parthasarathi2020task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.04826"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Applications']
---
Task-oriented dialogue systems help users accomplish tasks such as booking a
movie ticket and ordering food via conversation. Generative models
parameterized by a deep neural network are widely used for next turn response
generation in such systems. It is natural for users of the system to want to
accomplish multiple tasks within the same conversation, but the ability of
generative models to compose multiple tasks is not well studied. In this work,
we begin by studying the effect of training human-human task-oriented dialogues
towards improving the ability to compose multiple tasks on Transformer
generative models. To that end, we propose and explore two solutions: (1)
creating synthetic multiple task dialogue data for training from human-human
single task dialogue and (2) forcing the encoder representation to be invariant
to single and multiple task dialogues using an auxiliary loss. The results from
our experiments highlight the difficulty of even the sophisticated variant of
transformer model in learning to compose multiple tasks from single task
dialogues.
