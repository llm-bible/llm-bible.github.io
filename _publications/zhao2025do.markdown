---
layout: publication
title: 'Do We Know What Llms Don''t Know? A Study Of Consistency In Knowledge Probing'
authors: Raoyuan Zhao, Abdullatif Köksal, Ali Modarressi, Michael A. Hedderich, Hinrich Schütze
conference: "Arxiv"
year: 2025
bibkey: zhao2025do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21701'}
tags: ['Prompting', 'Tools']
---
The reliability of large language models (LLMs) is greatly compromised by their tendency to hallucinate, underscoring the need for precise identification of knowledge gaps within LLMs. Various methods for probing such gaps exist, ranging from calibration-based to prompting-based methods. To evaluate these probing methods, in this paper, we propose a new process based on using input variations and quantitative metrics. Through this, we expose two dimensions of inconsistency in knowledge gap probing. (1) Intra-method inconsistency: Minimal non-semantic perturbations in prompts lead to considerable variance in detected knowledge gaps within the same probing method; e.g., the simple variation of shuffling answer options can decrease agreement to around 40%. (2) Cross-method inconsistency: Probing methods contradict each other on whether a model knows the answer. Methods are highly inconsistent -- with decision consistency across methods being as low as 7% -- even though the model, dataset, and prompt are all the same. These findings challenge existing probing methods and highlight the urgent need for perturbation-robust probing frameworks.
