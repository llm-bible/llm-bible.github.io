---
layout: publication
title: 'Shifting Perspectives: Steering Vector Ensembles For Robust Bias Mitigation In Llms'
authors: Zara Siddique, Irtaza Khalid, Liam D. Turner, Luis Espinosa-anke
conference: "Arxiv"
year: 2025
bibkey: siddique2025shifting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05371'}
tags: ['RAG', 'Efficiency and Optimization', 'Merging', 'Bias Mitigation', 'Ethics and Bias', 'Responsible AI']
---
We present a novel approach to bias mitigation in large language models
(LLMs) by applying steering vectors to modify model activations in forward
passes. We employ Bayesian optimization to systematically identify effective
contrastive pair datasets across nine bias axes. When optimized on the BBQ
dataset, our individually tuned steering vectors achieve average improvements
of 12.2%, 4.7%, and 3.2% over the baseline for Mistral, Llama, and Qwen,
respectively. Building on these promising results, we introduce Steering Vector
Ensembles (SVE), a method that averages multiple individually optimized
steering vectors, each targeting a specific bias axis such as age, race, or
gender. By leveraging their collective strength, SVE outperforms individual
steering vectors in both bias reduction and maintaining model performance. The
work presents the first systematic investigation of steering vectors for bias
mitigation, and we demonstrate that SVE is a powerful and computationally
efficient strategy for reducing bias in LLMs, with broader implications for
enhancing AI safety.
