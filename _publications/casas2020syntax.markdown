---
layout: publication
title: 'Syntax-driven Iterative Expansion Language Models For Controllable Text Generation'
authors: Noe Casas, José A. R. Fonollosa, Marta R. Costa-jussà
conference: "Arxiv"
year: 2020
bibkey: casas2020syntax
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2004.02211'}
tags: ['Language Modeling', 'Transformer', 'Model Architecture', 'Applications', 'Ethics and Bias', 'Pretraining Methods']
---
The dominant language modeling paradigm handles text as a sequence of
discrete tokens. While that approach can capture the latent structure of the
text, it is inherently constrained to sequential dynamics for text generation.
We propose a new paradigm for introducing a syntactic inductive bias into
neural text generation, where the dependency parse tree is used to drive the
Transformer model to generate sentences iteratively.
  Our experiments show that this paradigm is effective at text generation, with
quality between LSTMs and Transformers, and comparable diversity, requiring
less than half their decoding steps, and its generation process allows direct
control over the syntactic constructions of the generated text, enabling the
induction of stylistic variations.
