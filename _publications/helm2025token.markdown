---
layout: publication
title: 'Token Weighting For Long-range Language Modeling'
authors: Falko Helm, Nico Daheim, Iryna Gurevych
conference: "Arxiv"
year: 2025
bibkey: helm2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.09202"}
tags: ['Training Techniques', 'Language Modeling', 'Tools', 'Applications']
---
Many applications of large language models (LLMs) require long-context
understanding, but models continue to struggle with such tasks. We hypothesize
that conventional next-token prediction training could contribute to this,
because each token is assigned equal weight. Yet, intuitively, the amount of
context needed to predict the next token accurately varies greatly across
different data. To reflect this, we propose various novel token-weighting
schemes that assign different weights to each training token in the loss,
thereby generalizing existing works. For this, we categorize token-weighting
methods using a two-step framework which compares the confidences of a
long-context and short-context model to score tokens. We evaluate all methods
on multiple long-context understanding tasks and show that non-uniform loss
weights are helpful to improve the long-context abilities of LLMs. Different
short-context models can be used effectively for token scoring, including
models that are much smaller than the long-context model that is trained. All
in all, this work contributes to a better understanding of the trade-offs
long-context language modeling faces and provides guidelines for model steering
via loss-weighting based on empirical evidence. The code can be found on
Github.
