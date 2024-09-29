---
layout: publication
title: Spin glass model of in-context learning
authors: Li Yuhao, Bai Ruoran, Huang Haiping
conference: "Arxiv"
year: 2024
bibkey: li2024spin
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02288"}
tags: ['Attention Mechanism', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Large language models show a surprising in-context learning ability -- being able to use a prompt to form a prediction for a query yet without additional training in stark contrast to old-fashioned supervised learning. Providing a mechanistic interpretation and linking the empirical phenomenon to physics are thus challenging and remain unsolved. We study a simple yet expressive transformer with linear attention and map this structure to a spin glass model with real-valued spins where the couplings and fields explain the intrinsic disorder in data. The spin glass model explains how the weight parameters interact with each other during pre-training and most importantly why an unseen function can be predicted by providing only a prompt yet without training. Our theory reveals that for single instance learning increasing the task diversity leads to the emergence of the in-context learning by allowing the Boltzmann distribution to converge to a unique correct solution of weight parameters. Therefore the pre-trained transformer displays a prediction power in a novel prompt setting. The proposed spin glass model thus establishes a foundation to understand the empirical success of large language models.
