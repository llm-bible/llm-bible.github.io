---
layout: publication
title: 'Why Gradients Rapidly Increase Near The End Of Training'
authors: Aaron Defazio
conference: "Arxiv"
year: 2025
bibkey: defazio2025why
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02285'}
tags: ['Tools', 'Training Techniques']
---
During long-duration Large Language Model (LLM) training runs the gradient norm increases rapidly near the end of training. In this short note, we show that this increase is due to an unintended interaction between weight decay, normalization layers, and the learning rate schedule. We propose a simple correction that fixes this behavior while also resulting in lower loss values throughout training.
