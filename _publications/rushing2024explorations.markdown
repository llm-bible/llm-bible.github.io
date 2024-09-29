---
layout: publication
title: 'Explorations Of Self-repair In Language Models'
authors: Rushing Cody, Nanda Neel
conference: "Arxiv"
year: 2024
bibkey: rushing2024explorations
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15390"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques']
---
Prior interpretability research studying narrow distributions has preliminarily identified self-repair a phenomena where if components in large language models are ablated later components will change their behavior to compensate. Our work builds off this past literature demonstrating that self-repair exists on a variety of models families and sizes when ablating individual attention heads on the full training distribution. We further show that on the full training distribution self-repair is imperfect as the original direct effect of the head is not fully restored and noisy since the degree of self-repair varies significantly across different prompts (sometimes overcorrecting beyond the original effect). We highlight two different mechanisms that contribute to self-repair including changes in the final LayerNorm scaling factor and sparse sets of neurons implementing Anti-Erasure. We additionally discuss the implications of these results for interpretability practitioners and close with a more speculative discussion on the mystery of why self-repair occurs in these models at all highlighting evidence for the Iterative Inference hypothesis in language models a framework that predicts self-repair.
