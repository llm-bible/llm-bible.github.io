---
layout: publication
title: 'Think Global, Act Local: Dual-scale Graph Transformer For Vision-and-language
  Navigation'
authors: Shizhe Chen, Pierre-louis Guhur, Makarand Tapaswi, Cordelia Schmid, Ivan
  Laptev
conference: Arxiv
year: 2022
citations: 82
bibkey: chen2022think
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.11742'}]
tags: [Transformer, Fine-Tuning, Agentic, Multimodal Models]
---
Following language instructions to navigate in unseen environments is a
challenging problem for autonomous embodied agents. The agent not only needs to
ground languages in visual scenes, but also should explore the environment to
reach its target. In this work, we propose a dual-scale graph transformer
(DUET) for joint long-term action planning and fine-grained cross-modal
understanding. We build a topological map on-the-fly to enable efficient
exploration in global action space. To balance the complexity of large action
space reasoning and fine-grained language grounding, we dynamically combine a
fine-scale encoding over local observations and a coarse-scale encoding on a
global map via graph transformers. The proposed approach, DUET, significantly
outperforms state-of-the-art methods on goal-oriented vision-and-language
navigation (VLN) benchmarks REVERIE and SOON. It also improves the success rate
on the fine-grained VLN benchmark R2R.