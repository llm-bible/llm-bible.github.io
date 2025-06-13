---
layout: publication
title: 'Balcony: A Lightweight Approach To Dynamic Inference Of Generative Language Models'
authors: Benyamin Jamialahmadi, Parsa Kavehzadeh, Mehdi Rezagholizadeh, Parsa Farinneya, Hossein Rajabzadeh, Aref Jafari, Boxing Chen, Marzieh S. Tahaei
conference: "Arxiv"
year: 2025
bibkey: jamialahmadi2025lightweight
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05005'}
tags: ['Transformer', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Applications', 'Tools', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods']
---
Deploying large language models (LLMs) in real-world applications is often
hindered by strict computational and latency constraints. While dynamic
inference offers the flexibility to adjust model behavior based on varying
resource budgets, existing methods are frequently limited by hardware
inefficiencies or performance degradation. In this paper, we introduce Balcony,
a simple yet highly effective framework for depth-based dynamic inference. By
freezing the pretrained LLM and inserting additional transformer layers at
selected exit points, Balcony maintains the full model's performance while
enabling real-time adaptation to different computational budgets. These
additional layers are trained using a straightforward self-distillation loss,
aligning the sub-model outputs with those of the full model. This approach
requires significantly fewer training tokens and tunable parameters,
drastically reducing computational costs compared to prior methods. When
applied to the LLaMA3-8B model, using only 0.2% of the original pretraining
data, Balcony achieves minimal performance degradation while enabling
significant speedups. Remarkably, we show that Balcony outperforms
state-of-the-art methods such as Flextron and Layerskip as well as other
leading compression techniques on multiple models and at various scales, across
a variety of benchmarks.
