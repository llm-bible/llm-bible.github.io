---
layout: publication
title: 'How Abstract Is Linguistic Generalization In Large Language Models? Experiments With Argument Structure'
authors: Michael Wilson, Jackson Petty, Robert Frank
conference: "Arxiv"
year: 2023
bibkey: wilson2023how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.04900'}
  - {name: "Code", url: 'https://github.com/clay-lab/structural-alternations'}
tags: ['Has Code', 'Transformer', 'Ethics and Bias', 'Training Techniques', 'Model Architecture', 'Pre-Training', 'Pretraining Methods']
---
Language models are typically evaluated on their success at predicting the
distribution of specific words in specific contexts. Yet linguistic knowledge
also encodes relationships between contexts, allowing inferences between word
distributions. We investigate the degree to which pre-trained Transformer-based
large language models (LLMs) represent such relationships, focusing on the
domain of argument structure. We find that LLMs perform well in generalizing
the distribution of a novel noun argument between related contexts that were
seen during pre-training (e.g., the active object and passive subject of the
verb spray), succeeding by making use of the semantically-organized structure
of the embedding space for word embeddings. However, LLMs fail at
generalizations between related contexts that have not been observed during
pre-training, but which instantiate more abstract, but well-attested structural
generalizations (e.g., between the active object and passive subject of an
arbitrary verb). Instead, in this case, LLMs show a bias to generalize based on
linear order. This finding points to a limitation with current models and
points to a reason for which their training is data-intensive.s reported here
are available at https://github.com/clay-lab/structural-alternations.
