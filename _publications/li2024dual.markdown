---
layout: publication
title: 'Dual Diffusion For Unified Image Generation And Understanding'
authors: Zijie Li, Henry Li, Yichun Shi, Amir Barati Farimani, Yuval Kluger, Linjie Yang, Peng Wang
conference: "Arxiv"
year: 2024
bibkey: li2024dual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00289"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Language Modeling', 'GPT', 'Merging', 'Pretraining Methods', 'Transformer', 'Applications']
---
Diffusion models have gained tremendous success in text-to-image generation,
yet still lag behind with visual understanding tasks, an area dominated by
autoregressive vision-language models. We propose a large-scale and fully
end-to-end diffusion model for multi-modal understanding and generation that
significantly improves on existing diffusion-based multimodal models, and is
the first of its kind to support the full suite of vision-language modeling
capabilities. Inspired by the multimodal diffusion transformer (MM-DiT) and
recent advances in discrete diffusion language modeling, we leverage a
cross-modal maximum likelihood estimation framework that simultaneously trains
the conditional likelihoods of both images and text jointly under a single loss
function, which is back-propagated through both branches of the diffusion
transformer. The resulting model is highly flexible and capable of a wide range
of tasks including image generation, captioning, and visual question answering.
Our model attained competitive performance compared to recent unified image
understanding and generation models, demonstrating the potential of multimodal
diffusion modeling as a promising alternative to autoregressive next-token
prediction models.
