---
layout: publication
title: 'Efficient Few-shot Continual Learning In Vision-language Models'
authors: Aristeidis Panos, Rahaf Aljundi, Daniel Olmeda Reino, Richard E. Turner
conference: "Arxiv"
year: 2025
bibkey: panos2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04098"}
tags: ['Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Security', 'Few-Shot', 'Multimodal Models']
---
Vision-language models (VLMs) excel in tasks such as visual question
answering and image captioning. However, VLMs are often limited by their use of
pretrained image encoders, like CLIP, leading to image understanding errors
that hinder overall performance. On top of that, real-world applications often
require the model to be continuously adapted as new and often limited data
continuously arrive. To address this, we propose LoRSU (Low-Rank Adaptation
with Structured Updates), a robust and computationally efficient method for
selectively updating image encoders within VLMs. LoRSU introduces structured
and localized parameter updates, effectively correcting performance on
previously error-prone data while preserving the model's general robustness.
Our approach leverages theoretical insights to identify and update only the
most critical parameters, achieving significant resource efficiency.
Specifically, we demonstrate that LoRSU reduces computational overhead by over
25x compared to full VLM updates, without sacrificing performance. Experimental
results on VQA tasks in the few-shot continual learning setting, validate
LoRSU's scalability, efficiency, and effectiveness, making it a compelling
solution for image encoder adaptation in resource-constrained environments.
