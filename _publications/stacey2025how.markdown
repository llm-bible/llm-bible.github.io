---
layout: publication
title: 'How To Improve The Robustness Of Closed-source Models On NLI'
authors: Joe Stacey, Lisa Alazraki, Aran Ubhi, Beyza Ermis, Aaron Mueller, Marek Rei
conference: "Arxiv"
year: 2025
bibkey: stacey2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20209"}
tags: ['GPT', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Closed-source Large Language Models (LLMs) have become increasingly popular, with impressive performance across a wide range of natural language tasks. These models can be fine-tuned to further improve performance, but this often results in the models learning from dataset-specific heuristics that reduce their robustness on out-of-distribution (OOD) data. Existing methods to improve robustness either perform poorly, or are non-applicable to closed-source models because they assume access to model internals, or the ability to change the model's training procedure. In this work, we investigate strategies to improve the robustness of closed-source LLMs through data-centric methods that do not require access to model internals. We find that the optimal strategy depends on the complexity of the OOD data. For highly complex OOD datasets, upsampling more challenging training examples can improve robustness by up to 1.5%. For less complex OOD datasets, replacing a portion of the training set with LLM-generated examples can improve robustness by 3.7%. More broadly, we find that large-scale closed-source autoregressive LLMs are substantially more robust than commonly used encoder models, and are a more appropriate choice of baseline going forward.
