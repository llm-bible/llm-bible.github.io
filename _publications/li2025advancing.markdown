---
layout: publication
title: 'Advancing Multimodal In-context Learning In Large Vision-language Models With Task-aware Demonstrations'
authors: Yanshu Li
conference: "Arxiv"
year: 2025
bibkey: li2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04839"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'In-Context Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Prompting', 'Attention Mechanism']
---
Multimodal in-context learning (ICL) has emerged as a key capability of Large
Vision-Language Models (LVLMs), driven by their increasing scale and
applicability. Despite its promise, effective ICL in the multimodal setting
remains challenging due to the inherent complexity of image-text inputs and the
high sensitivity of ICL performance to input configurations. In this work, we
shed light on the core mechanism underlying multimodal ICL, identifying task
mapping as a crucial factor in configuring robust in-context demonstration
(ICD) sequences. Building on these insights, we propose \textit\{SabER\}, a
lightweight yet powerful decoder-only transformer equipped with task-aware
attention, which intelligently selects and arranges ICDs from a demonstration
library in an autoregressive fashion. This design enables fine-grained feature
extraction and cross-modal reasoning, iteratively refining task mapping to
generate high-quality ICD sequences. Through extensive experiments covering
five LVLMs and nine benchmark datasets, SabER not only demonstrates strong
empirical performance, but also provides deeper understanding of how task
semantics interact with multimodal ICDs. Our findings highlight the importance
of principled ICD sequence configuration and open new avenues to enhance
multimodal ICL in a wide range of real-world scenarios.
