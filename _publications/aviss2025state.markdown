---
layout: publication
title: 'State Stream Transformer (SST) : Emergent Metacognitive Behaviours Through Latent State Persistence'
authors: Thea Aviss
conference: "Arxiv"
year: 2025
bibkey: aviss2025state
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.18356'}
tags: ['GPT', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
We introduce the State Stream Transformer (SST), a novel LLM architecture
that reveals emergent reasoning behaviours and capabilities latent in
pretrained weights through addressing a fundamental limitation in traditional
transformer models: the lack of latent computational continuity across
autoregressive generations in the state space. SST introduces a sliding window
latent state (FFN) cache with weighted decay that maintains and evolves
persistent latent processes throughout autoregressive generations. Through
controlled experiments comparing base and SST architectures using the same
frozen weights, we demonstrate that this architectural modification alone
enables enhanced reasoning capabilities which appear best explained by some
form of potential higher-order processing, as evidenced by emergent
metacognitive behaviours. These behaviours persist under controlled conditions
designed to eliminate confounding factors such as stochastic variation or
learned response patterns. Analysis of latent state distributions and
processing dynamics provides evidence that it is solely the 'state stream' that
is responsible for these phenomena. In quantitative evaluations, the SST
achieves substantial performance improvements over the base model on two
reasoning benchmarks, reaching 89.01% accuracy on GSM-8K (0-shot) and 91.04%
on ARC Challenge (0-shot CoT). These findings indicate that persistent
computation in the latent state space enables fundamentally different
information processing and internal reasoning strategies, with implications for
our understanding of artificial intelligence systems.
