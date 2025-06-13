---
layout: publication
title: 'Let''s Think Dot By Dot: Hidden Computation In Transformer Language Models'
authors: Jacob Pfau, William Merrill, Samuel R. Bowman
conference: "Arxiv"
year: 2024
bibkey: pfau2024think
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.15758'}
tags: ['Transformer', 'Model Architecture', 'Pretraining Methods']
---
Chain-of-thought responses from language models improve performance across
most benchmarks. However, it remains unclear to what extent these performance
gains can be attributed to human-like task decomposition or simply the greater
computation that additional tokens allow. We show that transformers can use
meaningless filler tokens (e.g., '......') in place of a chain of thought to
solve two hard algorithmic tasks they could not solve when responding without
intermediate tokens. However, we find empirically that learning to use filler
tokens is difficult and requires specific, dense supervision to converge. We
also provide a theoretical characterization of the class of problems where
filler tokens are useful in terms of the quantifier depth of a first-order
formula. For problems satisfying this characterization, chain-of-thought tokens
need not provide information about the intermediate computational steps
involved in multi-token computations. In summary, our results show that
additional tokens can provide computational benefits independent of token
choice. The fact that intermediate tokens can act as filler tokens raises
concerns about large language models engaging in unauditable, hidden
computations that are increasingly detached from the observed chain-of-thought
tokens.
