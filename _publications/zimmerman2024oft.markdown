---
layout: publication
title: 'Tokens, The Oft-overlooked Appetizer: Large Language Models, The Distributional Hypothesis, And Meaning'
authors: Julia Witte Zimmerman, Denis Hudon, Kathryn Cramer, Alejandro J. Ruiz, Calla Beauregard, Ashley Fehr, Mikaela Irene Fudolig, Bradford Demarest, Yoshi Meke Bird, Milo Z. Trujillo, Christopher M. Danforth, Peter Sheridan Dodds
conference: "Arxiv"
year: 2024
bibkey: zimmerman2024oft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10924"}
tags: ['Transformer', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'BERT', 'Arxiv']
---
Tokenization is a necessary component within the current architecture of many
language models, including the transformer-based large language models (LLMs)
of Generative AI, yet its impact on the model's cognition is often overlooked.
We argue that LLMs demonstrate that the Distributional Hypothesis (DH) is
sufficient for reasonably human-like language performance, and that the
emergence of human-meaningful linguistic units among tokens and current
structural constraints motivate changes to existing, linguistically-agnostic
tokenization techniques, particularly with respect to their roles as (1)
semantic primitives and as (2) vehicles for conveying salient distributional
patterns from human language to the model. We explore tokenizations from a BPE
tokenizer; extant model vocabularies obtained from Hugging Face and tiktoken;
and the information in exemplar token vectors as they move through the layers
of a RoBERTa (large) model. Besides creating sub-optimal semantic building
blocks and obscuring the model's access to the necessary distributional
patterns, we describe how tokens and pretraining can act as a backdoor for bias
and other unwanted content, which current alignment practices may not
remediate. Additionally, we relay evidence that the tokenization algorithm's
objective function impacts the LLM's cognition, despite being arguably
meaningfully insulated from the main system intelligence. [First uploaded to
arXiv in December, 2024.]
