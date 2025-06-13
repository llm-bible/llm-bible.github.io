---
layout: publication
title: 'Popalign: Population-level Alignment For Fair Text-to-image Generation'
authors: Shufan Li, Harkanwar Singh, Aditya Grover
conference: "Arxiv"
year: 2024
bibkey: li2024population
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.19668'}
  - {name: "Code", url: 'https://github.com/jacklishufan/PopAlignSDXL'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias']
---
Text-to-image (T2I) models achieve high-fidelity generation through extensive
training on large datasets. However, these models may unintentionally pick up
undesirable biases of their training data, such as over-representation of
particular identities in gender or ethnicity neutral prompts. Existing
alignment methods such as Reinforcement Learning from Human Feedback (RLHF) and
Direct Preference Optimization (DPO) fail to address this problem effectively
because they operate on pairwise preferences consisting of individual samples,
while the aforementioned biases can only be measured at a population level. For
example, a single sample for the prompt "doctor" could be male or female, but a
model generating predominantly male doctors even with repeated sampling
reflects a gender bias. To address this limitation, we introduce PopAlign, a
novel approach for population-level preference optimization, while standard
optimization would prefer entire sets of samples over others. We further derive
a stochastic lower bound that directly optimizes for individual samples from
preferred populations over others for scalable training. Using human evaluation
and standard image quality and bias metrics, we show that PopAlign
significantly mitigates the bias of pretrained T2I models while largely
preserving the generation quality. Code is available at
https://github.com/jacklishufan/PopAlignSDXL.
