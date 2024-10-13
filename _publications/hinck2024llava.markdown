---
layout: publication
title: 'Llava-gemma: Accelerating Multimodal Foundation Models With A Compact Language Model'
authors: Hinck Musashi, Olson Matthew L., Cobbley David, Tseng Shao-yen, Lal Vasudev
conference: "Arxiv"
year: 2024
bibkey: hinck2024llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01331"}
tags: ['Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We train a suite of multimodal foundation models (MMFM) using the popular
LLaVA framework with the recently released Gemma family of large language
models (LLMs). Of particular interest is the 2B parameter Gemma model, which
provides opportunities to construct capable small-scale MMFMs. In line with
findings from other papers in this space, we test the effect of ablating three
design features: pretraining the connector, utilizing a more powerful image
backbone, and increasing the size of the language backbone. The resulting
models, which we call LLaVA-Gemma, exhibit moderate performance on an array of
evaluations, but fail to improve past the current comparably sized SOTA models.
Closer analysis of performance shows mixed effects; skipping pretraining tends
to reduce performance, larger vision models sometimes improve performance, and
increasing language model size has inconsistent effects. We publicly release
training recipes, code and weights for our models for the LLaVA-Gemma models.
