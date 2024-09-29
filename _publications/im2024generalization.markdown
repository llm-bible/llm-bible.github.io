---
layout: publication
title: 'On The Generalization Of Preference Learning With DPO'
authors: Im Shawn, Li Yixuan
conference: "Arxiv"
year: 2024
bibkey: im2024generalization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03459"}
tags: ['Efficiency And Optimization', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have demonstrated remarkable capabilities but often struggle to align with human preferences leading to harmful or undesirable outputs. Preference learning which trains models to distinguish between preferred and non-preferred responses based on human feedback has become a crucial component for ensuring that LLMs align with human values. Despite the widespread adoption in real-world systems a thorough theoretical understanding of the generalization guarantees for these models remain lacking. This paper bridges that gap by introducing a new theoretical framework to analyze the generalization guarantees of models trained with direct preference optimization (DPO). While existing generalization theory often focuses on overparameterized models achieving near-optimal loss or models independent of the training process our framework rigorously assesses how well models generalize after a finite number of gradient steps reflecting real-world LLM training practices. By analyzing the reward margin associated with each sample and its trajectory throughout training we can effectively bound the generalization error. We derive learning guarantees showing that under specific conditions models trained with DPO can correctly discern preferred responses on unseen data with high probability. These insights are empirically validated on contemporary LLMs underscoring the practical relevance of our theoretical findings.
