---
layout: publication
title: 'Towards Compatible Fine-tuning For Vision-language Model Updates'
authors: Zhengbo Wang, Jian Liang, Lijun Sheng, Ran He, Zilei Wang, Tieniu Tan
conference: "Arxiv"
year: 2024
bibkey: wang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20895"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
So far, efficient fine-tuning has become a popular strategy for enhancing the
capabilities of foundation models on downstream tasks by learning plug-and-play
modules. However, existing methods overlook a crucial issue: if the underlying
foundation model is updated, are these plug-and-play modules still effective?
In this paper, we first conduct a detailed analysis of various fine-tuning
methods on the CLIP in terms of their compatibility with model updates. The
study reveals that many high-performing fine-tuning methods fail to be
compatible with the upgraded models. To address this, we propose a novel
approach, Class-conditioned Context Optimization (ContCoOp), which integrates
learnable prompts with class embeddings using an attention layer before
inputting them into the text encoder. Consequently, the prompts can dynamically
adapt to the changes in embedding space (due to model updates), ensuring
continued effectiveness. Extensive experiments over 15 datasets show that our
ContCoOp achieves the highest compatibility over the baseline methods, and
exhibits robust out-of-distribution generalization.
