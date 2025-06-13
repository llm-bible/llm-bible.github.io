---
layout: publication
title: 'Regla: Refining Gated Linear Attention'
authors: Peng Lu, Ivan Kobyzev, Mehdi Rezagholizadeh, Boxing Chen, Philippe Langlais
conference: "Arxiv"
year: 2025
bibkey: lu2025refining
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01578'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Recent advancements in Large Language Models (LLMs) have set themselves apart
with their exceptional performance in complex language modelling tasks.
However, these models are also known for their significant computational and
storage requirements, primarily due to the quadratic computation complexity of
softmax attention. To mitigate this issue, linear attention has been designed
to reduce the quadratic space-time complexity that is inherent in standard
transformers. In this work, we embarked on a comprehensive exploration of three
key components that substantially impact the performance of the Gated Linear
Attention module: feature maps, normalization, and the gating mechanism. We
developed a feature mapping function to address some crucial issues that
previous suggestions overlooked. Then we offered further rationale for the
integration of normalization layers to stabilize the training process.
Moreover, we explored the saturation phenomenon of the gating mechanism and
augmented it with a refining module. We conducted extensive experiments and
showed our architecture outperforms previous Gated Linear Attention mechanisms
in extensive tasks including training from scratch and post-linearization with
continual pre-training.
