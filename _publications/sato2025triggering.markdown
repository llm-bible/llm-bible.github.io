---
layout: publication
title: 'Triggering Hallucinations In Llms: A Quantitative Study Of Prompt-induced Hallucination In Large Language Models'
authors: Makoto Sato
conference: "Arxiv"
year: 2025
bibkey: sato2025triggering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00557'}
tags: ['Security', 'Tools', 'Applications', 'Merging', 'Prompting', 'Reinforcement Learning']
---
Hallucinations in large language models (LLMs) present a growing challenge
across real-world applications, from healthcare to law, where factual
reliability is essential. Despite advances in alignment and instruction tuning,
LLMs can still generate outputs that are fluent yet fundamentally untrue.
Understanding the cognitive dynamics that underlie these hallucinations remains
an open problem. In this study, we propose a prompt-based framework to
systematically trigger and quantify hallucination: a Hallucination-Inducing
Prompt (HIP), which synthetically fuses semantically distant concepts (e.g.,
periodic table of elements and tarot divination) in a misleading way, and a
Hallucination Quantifying Prompt (HQP), which scores the plausibility,
confidence, and coherence of the output. Controlled experiments across multiple
LLMs revealed that HIPs consistently produced less coherent and more
hallucinated responses than their null-fusion controls. These effects varied
across models, with reasoning-oriented LLMs showing distinct profiles from
general-purpose ones. Our framework provides a reproducible testbed for
studying hallucination vulnerability, and opens the door to developing safer,
more introspective LLMs that can detect and self-regulate the onset of
conceptual instability.
