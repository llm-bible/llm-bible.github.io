---
layout: publication
title: 'Block Selective Reprogramming For On-device Training Of Vision Transformers'
authors: Sreetama Sarkar, Souvik Kundu, Kai Zheng, Peter A. Beerel
conference: "Arxiv"
year: 2024
bibkey: sarkar2024block
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10951"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
The ubiquity of vision transformers (ViTs) for various edge applications,
including personalized learning, has created the demand for on-device
fine-tuning. However, training with the limited memory and computation power of
edge devices remains a significant challenge. In particular, the memory
required for training is much higher than that needed for inference, primarily
due to the need to store activations across all layers in order to compute the
gradients needed for weight updates. Previous works have explored reducing this
memory requirement via frozen-weight training as well storing the activations
in a compressed format. However, these methods are deemed inefficient due to
their inability to provide training or inference speedup. In this paper, we
first investigate the limitations of existing on-device training methods aimed
at reducing memory and compute requirements. We then present block selective
reprogramming (BSR) in which we fine-tune only a fraction of total blocks of a
pre-trained model and selectively drop tokens based on self-attention scores of
the frozen layers. To show the efficacy of BSR, we present extensive
evaluations on ViT-B and DeiT-S with five different datasets. Compared to the
existing alternatives, our approach simultaneously reduces training memory by
up to 1.4x and compute cost by up to 2x while maintaining similar accuracy. We
also showcase results for Mixture-of-Expert (MoE) models, demonstrating the
effectiveness of our approach in multitask learning scenarios.
