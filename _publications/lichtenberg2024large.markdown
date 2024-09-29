---
layout: publication
title: Large Language Models As Recommender Systems A Study Of Popularity Bias
authors: Lichtenberg Jan Malte, Buchholz Alexander, Schwöbel Pola
conference: "Arxiv"
year: 2024
bibkey: lichtenberg2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01285"}
tags: ['Ethics And Bias', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
The issue of popularity bias -- where popular items are disproportionately recommended overshadowing less popular but potentially relevant items -- remains a significant challenge in recommender systems. Recent advancements have seen the integration of general-purpose Large Language Models (LLMs) into the architecture of such systems. This integration raises concerns that it might exacerbate popularity bias given that the LLMs training data is likely dominated by popular items. However it simultaneously presents a novel opportunity to address the bias via prompt tuning. Our study explores this dichotomy examining whether LLMs contribute to or can alleviate popularity bias in recommender systems. We introduce a principled way to measure popularity bias by discussing existing metrics and proposing a novel metric that fulfills a series of desiderata. Based on our new metric we compare a simple LLM-based recommender to traditional recommender systems on a movie recommendation task. We find that the LLM recommender exhibits less popularity bias even without any explicit mitigation.
