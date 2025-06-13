---
layout: publication
title: 'Drivinggpt: Unifying Driving World Modeling And Planning With Multi-modal Autoregressive Transformers'
authors: Yuntao Chen, Yuqi Wang, Zhaoxiang Zhang
conference: "Arxiv"
year: 2024
bibkey: chen2024unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18607"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'GPT', 'Pretraining Methods', 'Transformer']
---
World model-based searching and planning are widely recognized as a promising
path toward human-level physical intelligence. However, current driving world
models primarily rely on video diffusion models, which specialize in visual
generation but lack the flexibility to incorporate other modalities like
action. In contrast, autoregressive transformers have demonstrated exceptional
capability in modeling multimodal data. Our work aims to unify both driving
model simulation and trajectory planning into a single sequence modeling
problem. We introduce a multimodal driving language based on interleaved image
and action tokens, and develop DrivingGPT to learn joint world modeling and
planning through standard next-token prediction. Our DrivingGPT demonstrates
strong performance in both action-conditioned video generation and end-to-end
planning, outperforming strong baselines on large-scale nuPlan and NAVSIM
benchmarks.
