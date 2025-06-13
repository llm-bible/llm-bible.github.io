---
layout: publication
title: 'Large Language Models Vote: Prompting For Rare Disease Identification'
authors: David Oniani, Jordan Hilsman, Hang Dong, Fengyi Gao, Shiven Verma, Yanshan Wang
conference: "Arxiv"
year: 2023
bibkey: oniani2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12890"}
tags: ['Prompting', 'Training Techniques', 'Few-Shot']
---
The emergence of generative Large Language Models (LLMs) emphasizes the need
for accurate and efficient prompting approaches. LLMs are often applied in
Few-Shot Learning (FSL) contexts, where tasks are executed with minimal
training data. FSL has become popular in many Artificial Intelligence (AI)
subdomains, including AI for health. Rare diseases affect a small fraction of
the population. Rare disease identification from clinical notes inherently
requires FSL techniques due to limited data availability. Manual data
collection and annotation is both expensive and time-consuming. In this paper,
we propose Models-Vote Prompting (MVP), a flexible prompting approach for
improving the performance of LLM queries in FSL settings. MVP works by
prompting numerous LLMs to perform the same tasks and then conducting a
majority vote on the resulting outputs. This method achieves improved results
to any one model in the ensemble on one-shot rare disease identification and
classification tasks. We also release a novel rare disease dataset for FSL,
available to those who signed the MIMIC-IV Data Use Agreement (DUA).
Furthermore, in using MVP, each model is prompted multiple times, substantially
increasing the time needed for manual annotation, and to address this, we
assess the feasibility of using JSON for automating generative LLM evaluation.
