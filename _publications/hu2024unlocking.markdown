---
layout: publication
title: 'Unlocking Tuning-free Few-shot Adaptability In Visual Foundation Models By Recycling Pre-tuned Loras'
authors: Zixuan Hu, Yongxian Wei, Li Shen, Chun Yuan, Dacheng Tao
conference: "Arxiv"
year: 2024
bibkey: hu2024unlocking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.02220'}
tags: ['Few-Shot', 'Tools', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Training Techniques', 'GPT', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) such as ChatGPT demonstrate strong few-shot
adaptability without requiring fine-tuning, positioning them ideal for
data-limited and real-time applications. However, this adaptability has not yet
been replicated in current Visual Foundation Models (VFMs), which require
explicit fine-tuning with sufficient tuning data. Besides, the
pretraining-finetuning paradigm has led to the surge of numerous task-specific
modular components, such as Low-Rank Adaptation (LoRA). For the first time, we
explore the potential of reusing diverse pre-tuned LoRAs without accessing
their original training data, to achieve tuning-free few-shot adaptation in
VFMs. Our framework, LoRA Recycle, distills a meta-LoRA from diverse pre-tuned
LoRAs with a meta-learning objective, using surrogate data generated inversely
from pre-tuned LoRAs themselves. The VFM, once equipped with the meta-LoRA, is
empowered to solve new few-shot tasks in a single forward pass, akin to the
in-context learning of LLMs. Additionally, we incorporate a double-efficient
mechanism tailored to our framework, significantly accelerating the
meta-training process while maintaining or even improving performance.
Extensive experiments across various few-shot classification benchmarks across
both in- and cross-domain scenarios demonstrate the superiority of our
framework.
