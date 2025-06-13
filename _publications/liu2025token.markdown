---
layout: publication
title: 'Token-level Uncertainty-aware Objective For Language Model Post-training'
authors: Tingkai Liu, Ari S. Benjamin, Anthony M. Zador
conference: "Arxiv"
year: 2025
bibkey: liu2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16511"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'GPT']
---
In the current work, we connect token-level uncertainty in causal language
modeling to two types of training objectives: 1) masked maximum likelihood
(MLE), 2) self-distillation. We show that masked MLE is effective in reducing
epistemic uncertainty, and serve as an effective token-level automatic
curriculum learning technique. However, masked MLE is prone to overfitting and
requires self-distillation regularization to improve or maintain performance on
out-of-distribution tasks. We demonstrate significant performance gain via the
proposed training objective - combined masked MLE and self-distillation -
across multiple architectures (Gemma, LLaMA, Phi) and datasets (Alpaca,
ShareGPT, GSM8K), mitigating overfitting while maintaining adaptability during
post-training. Our findings suggest that uncertainty-aware training provides an
effective mechanism for enhancing language model training.
