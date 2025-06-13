---
layout: publication
title: 'MMRL++: Parameter-efficient And Interaction-aware Representation Learning For Vision-language Models'
authors: Yuncheng Guo, Xiaodong Gu
conference: "Arxiv"
year: 2025
bibkey: guo2025parameter
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10088'}
tags: ['Few-Shot', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning']
---
Large-scale pre-trained Vision-Language Models (VLMs) have significantly advanced transfer learning across diverse tasks. However, adapting these models with limited few-shot data often leads to overfitting, undermining their ability to generalize to new tasks. To address this, we propose Multi-Modal Representation Learning (MMRL), which introduces a shared, learnable, modality-agnostic representation space. MMRL generates space tokens projected into both text and image encoders as representation tokens, enabling more effective cross-modal interactions. Unlike prior methods that mainly optimize class token features, MMRL inserts representation tokens into higher encoder layers--where task-specific features are more prominent--while preserving general knowledge in the lower layers. During training, both class and representation features are jointly optimized: a trainable projection layer is applied to representation tokens for task adaptation, while the projection layer for class token remains frozen to retain pre-trained knowledge. To further promote generalization, we introduce a regularization term aligning class and text features with the frozen VLM's zero-shot features. At inference, a decoupling strategy uses both class and representation features for base tasks, but only class features for novel tasks due to their stronger generalization. Building upon this, we propose MMRL++, a parameter-efficient and interaction-aware extension that significantly reduces trainable parameters and enhances intra-modal interactions--particularly across the layers of representation tokens--allowing gradient sharing and instance-specific information to propagate more effectively through the network. Extensive experiments on 15 datasets demonstrate that MMRL and MMRL++ consistently outperform state-of-the-art methods, achieving a strong balance between task-specific adaptation and generalization.
