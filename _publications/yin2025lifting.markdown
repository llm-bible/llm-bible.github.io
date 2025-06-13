---
layout: publication
title: 'Lifting The Veil On Visual Information Flow In Mllms: Unlocking Pathways To Faster Inference'
authors: Hao Yin, Guangzong Si, Zilei Wang
conference: "Arxiv"
year: 2025
bibkey: yin2025lifting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13108'}
tags: ['Pruning', 'Efficiency and Optimization', 'Multimodal Models']
---
Multimodal large language models (MLLMs) improve performance on
vision-language tasks by integrating visual features from pre-trained vision
encoders into large language models (LLMs). However, how MLLMs process and
utilize visual information remains unclear. In this paper, a shift in the
dominant flow of visual information is uncovered: (1) in shallow layers, strong
interactions are observed between image tokens and instruction tokens, where
most visual information is injected into instruction tokens to form cross-modal
semantic representations; (2) in deeper layers, image tokens primarily interact
with each other, aggregating the remaining visual information to optimize
semantic representations within visual modality. Based on these insights, we
propose Hierarchical Modality-Aware Pruning (HiMAP), a plug-and-play inference
acceleration method that dynamically prunes image tokens at specific layers,
reducing computational costs by approximately 65% without sacrificing
performance. Our findings offer a new understanding of visual information
processing in MLLMs and provide a state-of-the-art solution for efficient
inference.
