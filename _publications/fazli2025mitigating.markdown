---
layout: publication
title: 'Mitigating Hallucination In Large Vision-language Models Via Adaptive Attention Calibration'
authors: Mehrdad Fazli, Bowen Wei, Ziwei Zhu
conference: "Arxiv"
year: 2025
bibkey: fazli2025mitigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21472'}
tags: ['Attention Mechanism', 'Model Architecture', 'Tools', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
Large vision-language models (LVLMs) achieve impressive performance on multimodal tasks but often suffer from hallucination, and confidently describe objects or attributes not present in the image. Current inference-time interventions, while training-free, struggle to maintain accuracy in open-ended and long-form generation scenarios. We introduce the Confidence-Aware Attention Calibration (CAAC) framework to address this challenge by targeting two key biases: spatial perception bias, which distributes attention disproportionately across image tokens, and modality bias, which shifts focus from visual to textual inputs over time. CAAC employs a two-step approach: Visual-Token Calibration (VTC) to balance attention across visual tokens, and Adaptive Attention Re-Scaling (AAR) to reinforce visual grounding based on the model's confidence. This confidence-driven adjustment ensures consistent visual alignment during generation. Experiments on CHAIR, AMBER, and POPE benchmarks demonstrate that CAAC outperforms baselines, particularly in long-form generations, effectively reducing hallucination.
