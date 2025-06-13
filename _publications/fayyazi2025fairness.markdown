---
layout: publication
title: 'FACTER: Fairness-aware Conformal Thresholding And Prompt Engineering For Enabling Fair Llm-based Recommender Systems'
authors: Arya Fayyazi, Mehdi Kamal, Massoud Pedram
conference: "Arxiv"
year: 2025
bibkey: fayyazi2025fairness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02966'}
tags: ['RAG', 'Security', 'Fairness', 'Training Techniques', 'Tools', 'Prompting', 'RecSys', 'Bias Mitigation', 'Ethics and Bias']
---
We propose FACTER, a fairness-aware framework for LLM-based recommendation
systems that integrates conformal prediction with dynamic prompt engineering.
By introducing an adaptive semantic variance threshold and a
violation-triggered mechanism, FACTER automatically tightens fairness
constraints whenever biased patterns emerge. We further develop an adversarial
prompt generator that leverages historical violations to reduce repeated
demographic biases without retraining the LLM. Empirical results on MovieLens
and Amazon show that FACTER substantially reduces fairness violations (up to
95.5%) while maintaining strong recommendation accuracy, revealing semantic
variance as a potent proxy of bias.
