---
layout: publication
title: 'Truth-value Judgment In Language Models: Belief Directions Are Context Sensitive'
authors: Stefan F. Schouten, Peter Bloem, Ilia Markov, Piek Vossen
conference: "Arxiv"
year: 2024
bibkey: schouten2024truth
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.18865'}
tags: ['Reinforcement Learning']
---
Recent work has demonstrated that the latent spaces of large language models
(LLMs) contain directions predictive of the truth of sentences. Multiple
methods recover such directions and build probes that are described as getting
at a model's "knowledge" or "beliefs". We investigate this phenomenon, looking
closely at the impact of context on the probes. Our experiments establish where
in the LLM the probe's predictions can be described as being conditional on the
preceding (related) sentences. Specifically, we quantify the responsiveness of
the probes to the presence of (negated) supporting and contradicting sentences,
and score the probes on their consistency. We also perform a causal
intervention experiment, investigating whether moving the representation of a
premise along these belief directions influences the position of the hypothesis
along that same direction. We find that the probes we test are generally
context sensitive, but that contexts which should not affect the truth often
still impact the probe outputs. Our experiments show that the type of errors
depend on the layer, the (type of) model, and the kind of data. Finally, our
results suggest that belief directions are (one of the) causal mediators in the
inference process that incorporates in-context information.
