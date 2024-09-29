---
layout: publication
title: Test45;time Training On Nearest Neighbors For Large Language Models
authors: Hardt Moritz, Sun Yu
conference: "Arxiv"
year: 2023
bibkey: hardt2023test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18466"}
tags: ['GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Many recent efforts augment language models with retrieval by adding retrieved data to the input context. For this approach to succeed the retrieved data must be added at both training and test time. Moreover as input length grows linearly with the size of retrieved data cost in computation and memory grows quadratically for modern Transformers. To avoid these complications we simply fine45;tune the model on retrieved data at test time using its standard training setup. We build a large45;scale distributed index based on text embeddings of the Pile dataset. For each test input our system retrieves its neighbors and fine45;tunes the model on their text. Surprisingly retrieving and training on as few as 20 neighbors each for only one gradient iteration drastically improves performance across more than 20 language modeling tasks in the Pile. For example test45;time training with nearest neighbors significantly narrows the performance gap between a small GPT45;2 and a GPT45;Neo model more than 10 times larger. Sufficient index quality and size however are necessary. Our work establishes a first baseline of test45;time training for language modeling.
