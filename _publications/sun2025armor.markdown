---
layout: publication
title: 'ARMOR V0.1: Empowering Autoregressive Multimodal Understanding Model With Interleaved Multimodal Generation Via Asymmetric Synergy'
authors: Jianwen Sun, Yukang Feng, Chuanhao Li, Fanrui Zhang, Zizhen Li, Jiaxin Ai, Sizhuo Zhou, Yu Dai, Shenglin Zhang, Kaipeng Zhang
conference: "Arxiv"
year: 2025
bibkey: sun2025armor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06542"}
  - {name: "Code", url: "https://armor.github.io"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
Unified models (UniMs) for multimodal understanding and generation have
recently received much attention in the area of vision and language. Existing
UniMs are designed to simultaneously learn both multimodal understanding and
generation capabilities, demanding substantial computational resources, and
often struggle to generate interleaved text-image. We present ARMOR, a
resource-efficient and pure autoregressive framework that achieves both
understanding and generation by fine-tuning existing multimodal large language
models (MLLMs). Specifically, ARMOR extends existing MLLMs from three
perspectives: (1) For model architecture, an asymmetric encoder-decoder
architecture with a forward-switching mechanism is introduced to unify
embedding space integrating textual and visual modalities for enabling natural
text-image interleaved generation with minimal computational overhead. (2) For
training data, a meticulously curated, high-quality interleaved dataset is
collected for fine-tuning MLLMs. (3) For the training algorithm, we propose a
``what or how to generate" algorithm to empower existing MLLMs with multimodal
generation capabilities while preserving their multimodal understanding
capabilities, through three progressive training stages based on the collected
dataset. Experimental results demonstrate that ARMOR upgrades existing MLLMs to
UniMs with promising image generation capabilities, using limited training
resources. Our code will be released soon at https://armor.github.io.
