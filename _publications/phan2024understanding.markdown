---
layout: publication
title: 'Understanding And Mitigating Tokenization Bias In Language Models'
authors: Buu Phan, Marton Havasi, Matthew Muckley, Karen Ullrich
conference: "Arxiv"
year: 2024
bibkey: phan2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16829"}
tags: ['GPT', 'Ethics and Bias', 'Reinforcement Learning', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'Prompting']
---
State-of-the-art language models are autoregressive and operate on subword
units known as tokens. Specifically, one must encode the conditioning string
into a list of tokens before passing to the language models for next-token
prediction. We show that popular encoding schemes, such as maximum prefix
encoding (MPE) and byte-pair-encoding (BPE), induce a sampling bias that cannot
be mitigated with more training or data. To counter this universal problem, for
each encoding scheme above, we propose a novel algorithm to obtain unbiased
estimates from any language model trained on tokenized data. Our methods do not
require finetuning the model, and the complexity, defined as the number of
model runs, scales linearly with the sequence length in the case of MPE. As a
result, we show that one can simulate token-free behavior from a tokenized
language model. We empirically verify the correctness of our method through a
Markov-chain setup, where it accurately recovers the transition probabilities,
as opposed to the conventional method of directly prompting tokens into the
language model.
