---
layout: publication
title: 'ETA: Evaluating Then Aligning Safety Of Vision Language Models At Inference Time'
authors: Yi Ding, Bolian Li, Ruqi Zhang
conference: "Arxiv"
year: 2024
bibkey: ding2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.06625'}
  - {name: "Code", url: 'https://github.com/DripNowhy/ETA'}
tags: ['Has Code', 'Efficiency and Optimization', 'Security', 'GPT', 'Model Architecture', 'Tools', 'Multimodal Models', 'Reinforcement Learning', 'Responsible AI']
---
Vision Language Models (VLMs) have become essential backbones for multimodal
intelligence, yet significant safety challenges limit their real-world
application. While textual inputs are often effectively safeguarded,
adversarial visual inputs can easily bypass VLM defense mechanisms. Existing
defense methods are either resource-intensive, requiring substantial data and
compute, or fail to simultaneously ensure safety and usefulness in responses.
To address these limitations, we propose a novel two-phase inference-time
alignment framework, Evaluating Then Aligning (ETA): 1) Evaluating input visual
contents and output responses to establish a robust safety awareness in
multimodal settings, and 2) Aligning unsafe behaviors at both shallow and deep
levels by conditioning the VLMs' generative distribution with an interference
prefix and performing sentence-level best-of-N to search the most harmless and
helpful generation paths. Extensive experiments show that ETA outperforms
baseline methods in terms of harmlessness, helpfulness, and efficiency,
reducing the unsafe rate by 87.5% in cross-modality attacks and achieving 96.6%
win-ties in GPT-4 helpfulness evaluation. The code is publicly available at
https://github.com/DripNowhy/ETA.
