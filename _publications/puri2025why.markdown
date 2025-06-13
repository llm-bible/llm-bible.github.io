---
layout: publication
title: 'FADE: Why Bad Descriptions Happen To Good Features'
authors: Bruno Puri, Aakriti Jain, Elena Golimblevskaia, Patrick Kahardipraja, Thomas Wiegand, Wojciech Samek, Sebastian Lapuschkin
conference: "Arxiv"
year: 2025
bibkey: puri2025why
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16994'}
  - {name: "Code", url: 'https://github.com/brunibrun/FADE'}
tags: ['Reinforcement Learning', 'Has Code', 'Interpretability and Explainability', 'Tools']
---
Recent advances in mechanistic interpretability have highlighted the
potential of automating interpretability pipelines in analyzing the latent
representations within LLMs. While they may enhance our understanding of
internal mechanisms, the field lacks standardized evaluation methods for
assessing the validity of discovered features. We attempt to bridge this gap by
introducing FADE: Feature Alignment to Description Evaluation, a scalable
model-agnostic framework for evaluating feature-description alignment. FADE
evaluates alignment across four key metrics - Clarity, Responsiveness, Purity,
and Faithfulness - and systematically quantifies the causes for the
misalignment of feature and their description. We apply FADE to analyze
existing open-source feature descriptions, and assess key components of
automated interpretability pipelines, aiming to enhance the quality of
descriptions. Our findings highlight fundamental challenges in generating
feature descriptions, particularly for SAEs as compared to MLP neurons,
providing insights into the limitations and future directions of automated
interpretability. We release FADE as an open-source package at:
https://github.com/brunibrun/FADE.
