---
layout: publication
title: 'Flextron: Many-in-one Flexible Large Language Model'
authors: Cai Ruisi, Muralidharan Saurav, Heinrich Greg, Yin Hongxu, Wang Zhangyang, Kautz Jan, Molchanov Pavlo
conference: "Arxiv"
year: 2024
bibkey: cai2024many
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10260"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
"Training modern LLMs is extremely resource intensive, and customizing them for various deployment scenarios characterized by limited compute and memory resources through repeated training is impractical. In this paper, we introduce Flextron, a network architecture and post-training model optimization framework supporting flexible model deployment. The Flextron architecture utilizes a nested elastic structure to rapidly adapt to specific user-defined latency and accuracy targets during inference with no additional fine-tuning required. It is also input-adaptive, and can automatically route tokens through its sub-networks for improved performance and efficiency. We present a sample-efficient training method and associated routing algorithms for systematically transforming an existing trained LLM into a Flextron model. We evaluate Flextron on the GPT-3 and LLama-2 family of LLMs, and demonstrate superior performance over multiple end-to-end trained variants and other state-of-the-art elastic networks, all with a single pretraining run that consumes a mere 7.63&#37; tokens compared to original pretraining."
