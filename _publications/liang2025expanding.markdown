---
layout: publication
title: 'Expanding The Boundaries Of Vision Prior Knowledge In Multi-modal Large Language Models'
authors: Qiao Liang, Yanjiang Liu, Weixiang Zhou, Ben He, Yaojie Lu, Hongyu Lin, Jia Zheng, Xianpei Han, Le Sun, Yingfei Sun
conference: "Arxiv"
year: 2025
bibkey: liang2025expanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18034"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Does the prior knowledge of the vision encoder constrain the capability boundary of Multi-modal Large Language Models (MLLMs)? While most existing research treats MLLMs as unified systems optimized through end-to-end training, the impact of vision encoder's prior knowledge is seldom investigated. In this work, we introduce a novel metric, \\(Rank_e\\), to quantify the effect of prior knowledge of the vision encoder on MLLM performance. Our analysis reveals a positive correlation between prior knowledge and MLLM performance. Moreover, we find that domain-specific fine-tuning using solely end-to-end visual question answering (VQA) data is insufficient, particularly for entities with low inherent visual prior knowledge. To address this issue, we propose VisPRE (Vision Prior Remediation), a two-stage training framework that explicitly incorporates prior knowledge at the vision encoder level. Experimental results demonstrate that augmenting vision encoder's prior knowledge substantially boosts the visual understanding capabilities of MLLMs, offering a novel and effective strategy for improving performance, especially in scenarios involving uncommon visual entities.
