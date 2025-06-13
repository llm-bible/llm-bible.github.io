---
layout: publication
title: 'Order Matters: Exploring Order Sensitivity In Multimodal Large Language Models'
authors: Zhijie Tan, Xu Chu, Weiping Li, Tong Mo
conference: "Arxiv"
year: 2024
bibkey: tan2024order
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16983"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'In-Context Learning', 'Ethics and Bias', 'Prompting', 'Applications', 'Attention Mechanism']
---
Multimodal Large Language Models (MLLMs) utilize multimodal contexts
consisting of text, images, or videos to solve various multimodal tasks.
However, we find that changing the order of multimodal input can cause the
model's performance to fluctuate between advanced performance and random
guessing. This phenomenon exists in both single-modality (text-only or
image-only) and mixed-modality (image-text-pair) contexts. Furthermore, we
demonstrate that popular MLLMs pay special attention to certain multimodal
context positions, particularly the beginning and end. Leveraging this special
attention, we place key video frames and important image/text content in
special positions within the context and submit them to the MLLM for inference.
This method results in average performance gains of 14.7% for video-caption
matching and 17.8% for visual question answering tasks. Additionally, we
propose a new metric, Position-Invariant Accuracy (PIA), to address order bias
in MLLM evaluation. Our research findings contribute to a better understanding
of Multi-Modal In-Context Learning (MMICL) and provide practical strategies for
enhancing MLLM performance without increasing computational costs.
