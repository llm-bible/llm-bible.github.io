---
layout: publication
title: 'Boosting Performance On ARC Is A Matter Of Perspective'
authors: Daniel Franzen, Jan Disselhoff, David Hartmann
conference: "Arxiv"
year: 2025
bibkey: franzen2025boosting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.07859'}
tags: ['Ethics and Bias', 'Interpretability', 'RAG', 'Training Techniques']
---
The Abstraction and Reasoning Corpus (ARC-AGI) poses a significant challenge for large language models (LLMs), exposing limitations in their abstract reasoning abilities. In this work, we leverage task-specific data augmentations throughout the training, generation, and scoring phases, and employ a depth-first search algorithm to generate diverse, high-probability candidate solutions. Furthermore, we utilize the LLM not only as a generator but also as a scorer, using its output probabilities to select the most promising solutions. Our method achieves a score of 71.6% (286.5/400 solved tasks) on the public ARC-AGI evaluation set, demonstrating state-of-the-art performance among publicly available approaches. While concurrent closed-source work has reported higher scores, our method distinguishes itself through its transparency, reproducibility, and remarkably low inference cost, averaging only around 2ct per task on readily available hardware (we assume a price of 36ct/hour for a Nvidia 4090 GPU).
