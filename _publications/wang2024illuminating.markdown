---
layout: publication
title: 'ILLUME: Illuminating Your Llms To See, Draw, And Self-enhance'
authors: Chunwei Wang, Guansong Lu, Junwei Yang, Runhui Huang, Jianhua Han, Lu Hou, Wei Zhang, Hang Xu
conference: "Arxiv"
year: 2024
bibkey: wang2024illuminating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.06673'}
tags: ['Efficiency and Optimization', 'Multimodal Models', 'Training Techniques', 'Pretraining Methods']
---
In this paper, we introduce ILLUME, a unified multimodal large language model
(MLLM) that seamlessly integrates multimodal understanding and generation
capabilities within a single large language model through a unified next-token
prediction formulation. To address the large dataset size typically required
for image-text alignment, we propose to enhance data efficiency through the
design of a vision tokenizer that incorporates semantic information and a
progressive multi-stage training procedure. This approach reduces the dataset
size to just 15M for pretraining -- over four times fewer than what is
typically needed -- while achieving competitive or even superior performance
with existing unified MLLMs, such as Janus. Additionally, to promote
synergistic enhancement between understanding and generation capabilities,
which is under-explored in previous works, we introduce a novel self-enhancing
multimodal alignment scheme. This scheme supervises the MLLM to self-assess the
consistency between text descriptions and self-generated images, facilitating
the model to interpret images more accurately and avoid unrealistic and
incorrect predictions caused by misalignment in image generation. Based on
extensive experiments, our proposed ILLUME stands out and competes with
state-of-the-art unified MLLMs and specialized models across various benchmarks
for multimodal understanding, generation, and editing.
