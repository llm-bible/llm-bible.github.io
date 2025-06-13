---
layout: publication
title: 'Memorization Vs. Reasoning: Updating Llms With New Knowledge'
authors: Aochong Oliver Li, Tanya Goyal
conference: "Arxiv"
year: 2025
bibkey: li2025memorization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12523"}
tags: ['Pre-Training', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) encode vast amounts of pre-trained knowledge in
their parameters, but updating them as real-world information evolves remains a
challenge. Existing methodologies and benchmarks primarily target entity
substitutions, failing to capture the full breadth of complex real-world
dynamics. In this paper, we introduce Knowledge Update Playground (KUP), an
automatic pipeline for simulating realistic knowledge updates reflected in an
evidence corpora. KUP's evaluation framework includes direct and indirect
probes to both test memorization of updated facts and reasoning over them, for
any update learning methods. Next, we present a lightweight method called
memory conditioned training (MCT), which conditions tokens in the update corpus
on self-generated "memory" tokens during training. Our strategy encourages LLMs
to surface and reason over newly memorized knowledge at inference. Our results
on two strong LLMs show that (1) KUP benchmark is highly challenging, with the
best CPT models achieving \\(<2%\\) in indirect probing setting (reasoning) and
(2) MCT training significantly outperforms prior continued pre-training (CPT)
baselines, improving direct probing (memorization) results by up to \\(25.4%\\).
