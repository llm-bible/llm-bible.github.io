---
layout: publication
title: 'Investigating Language-specific Calibration For Pruning Multilingual Large Language Models'
authors: Simon Kurz, Jian-jia Chen, Lucie Flek, Zhixue Zhao
conference: "Arxiv"
year: 2024
bibkey: kurz2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14398"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Language Modeling', 'Pruning', 'Applications']
---
Recent advances in large language model (LLM) pruning have shown
state-of-the-art (SotA) compression results in post-training and
retraining-free settings while maintaining high predictive performance.
However, previous research mainly considered calibrating based on English text,
despite the multilingual nature of modern LLMs and their frequent use in
non-English languages. In this paper, we set out to investigate calibrating the
pruning of multilingual language models for monolingual applications. We
present the first comprehensive empirical study, comparing different
calibration languages for pruning multilingual models across diverse languages,
tasks, models, and SotA pruning techniques. Our results offer practical
suggestions, for example, calibrating in the target language can efficiently
retain the language modeling capability but does not necessarily benefit
downstream tasks. Through further analysis of latent subspaces, pruning masks,
and individual neurons within pruned models, we find that while pruning
generally preserves strong language-specific features, it may fail to retain
language-specific neuron activation patterns and subtle, language-agnostic
features associated with knowledge and reasoning that are needed for complex
tasks.
