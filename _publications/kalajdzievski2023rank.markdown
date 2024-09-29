---
layout: publication
title: A Rank Stabilization Scaling Factor for Fine-Tuning with LoRA
authors: Kalajdzievski Damjan
conference: "Arxiv"
year: 2023
bibkey: kalajdzievski2023rank
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.03732"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
As large language models (LLMs) have become increasingly compute and memory intensive parameter-efficient fine-tuning (PEFT) methods are now a common strategy to fine-tune LLMs. A popular PEFT method is Low-Rank Adapters (LoRA) which adds trainable low-rank adapters to selected layers. Each adapter consists of a low-rank matrix product multiplicatively scaled by a rank-dependent factor. This scaling factor which divides adapters by a factor of the rank results in slowed learning and stunted performance for LoRA with higher-rank adapters. Consequently the use of LoRA in practice has generally been limited to very low ranks. In this work we study the impact of the scaling factor on the learning process and prove that LoRA adapters should be divided by a factor of the square root of the rank. Modifying LoRA with the appropriate scaling factor which we call the rank-stabilized LoRA (rsLoRA) method easily provides for a fine-tuning compute/performance trade-off where larger ranks can be used to trade off increased computational resources during training for better fine-tuning performance with no change in inference computing cost.
