---
layout: publication
title: 'Identifying And Mitigating The Influence Of The Prior Distribution In Large Language Models'
authors: Liyi Zhang, Veniamin Veselovsky, R. Thomas Mccoy, Thomas L. Griffiths
conference: "Arxiv"
year: 2025
bibkey: zhang2025identifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12585'}
tags: ['Reinforcement Learning', 'Prompting', 'Interpretability and Explainability']
---
Large language models (LLMs) sometimes fail to respond appropriately to
deterministic tasks -- such as counting or forming acronyms -- because the
implicit prior distribution they have learned over sequences of tokens
influences their responses. In this work, we show that, in at least some cases,
LLMs actually compute the information needed to perform these tasks correctly,
and we identify some interventions that can allow them to access this
information to improve their performance. First, we show that simply prompting
the language model to not rely on its prior knowledge leads to dramatic
improvements in prior-dominated tasks. We then use mechanistic interpretability
techniques to localize the prior within the LLM and manipulate the extent to
which that prior influences its responses. Specifically, we show that it is
possible to identify layers of the underlying neural network that correlate
with the prior probability of a response and that lightweight finetuning of
these layers with basic prompts on prior-dominated tasks achieves high
performance on held-out answers. These results suggest that the information
required to produce a correct response is contained within the representations
of the problems formed by the models. Furthermore, we show that this finetuning
is significantly more effective for prior-dominated tasks, and that the error
after finetuning is no longer correlated with the prior. Our results suggest
that it may be possible to define effective methods for manipulating the extent
to which LLMs rely upon their priors in solving problems, potentially
increasing their performance in settings where LLMs hallucinate for reasons
related to the prior probability of token sequences.
