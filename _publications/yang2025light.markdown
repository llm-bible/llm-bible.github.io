---
layout: publication
title: 'Light As Deception: Gpt-driven Natural Relighting Against Vision-language Pre-training Models'
authors: Ying Yang, Jie Zhang, Xiao Lv, Di Lin, Tao Xiang, Qing Guo
conference: "Arxiv"
year: 2025
bibkey: yang2025light
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24227'}
tags: ['RAG', 'Efficiency and Optimization', 'Security', 'Model Architecture', 'Tools', 'Training Techniques', 'GPT', 'Applications', 'Multimodal Models', 'Pre-Training', 'Pretraining Methods']
---
While adversarial attacks on vision-and-language pretraining (VLP) models have been explored, generating natural adversarial samples crafted through realistic and semantically meaningful perturbations remains an open challenge. Existing methods, primarily designed for classification tasks, struggle when adapted to VLP models due to their restricted optimization spaces, leading to ineffective attacks or unnatural artifacts. To address this, we propose \textbf\{LightD\}, a novel framework that generates natural adversarial samples for VLP models via semantically guided relighting. Specifically, LightD leverages ChatGPT to propose context-aware initial lighting parameters and integrates a pretrained relighting model (IC-light) to enable diverse lighting adjustments. LightD expands the optimization space while ensuring perturbations align with scene semantics. Additionally, gradient-based optimization is applied to the reference lighting image to further enhance attack effectiveness while maintaining visual naturalness. The effectiveness and superiority of the proposed LightD have been demonstrated across various VLP models in tasks such as image captioning and visual question answering.
