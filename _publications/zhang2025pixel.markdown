---
layout: publication
title: 'Pixel-sail: Single Transformer For Pixel-grounded Understanding'
authors: Tao Zhang, Xiangtai Li, Zilong Huang, Yanwei Li, Weixian Lei, Xueqing Deng, Shihao Chen, Shunping Ji, Jiashi Feng
conference: "Arxiv"
year: 2025
bibkey: zhang2025pixel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10465"}
  - {name: "Code", url: "https://github.com/magic-research/Sa2VA"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Scaling Laws', 'Reinforcement Learning', 'Distillation', 'Merging', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting', 'Applications']
---
Multimodal Large Language Models (MLLMs) achieve remarkable performance for
fine-grained pixel-level understanding tasks. However, all the works rely
heavily on extra components, such as vision encoder (CLIP), segmentation
experts, leading to high system complexity and limiting model scaling. In this
work, our goal is to explore a highly simplified MLLM without introducing extra
components. Our work is motivated by the recent works on Single trAnsformer as
a unified vIsion-Language Model (SAIL) design, where these works jointly learn
vision tokens and text tokens in transformers. We present Pixel-SAIL, a single
transformer for pixel-wise MLLM tasks. In particular, we present three
technical improvements on the plain baseline. First, we design a learnable
upsampling module to refine visual token features. Secondly, we propose a novel
visual prompt injection strategy to enable the single transformer to understand
visual prompt inputs and benefit from the early fusion of visual prompt
embeddings and vision tokens. Thirdly, we introduce a vision expert
distillation strategy to efficiently enhance the single transformer's
fine-grained feature extraction capability. In addition, we have collected a
comprehensive pixel understanding benchmark (PerBench), using a manual check.
It includes three tasks: detailed object description, visual prompt-based
question answering, and visual-text referring segmentation. Extensive
experiments on four referring segmentation benchmarks, one visual prompt
benchmark, and our PerBench show that our Pixel-SAIL achieves comparable or
even better results with a much simpler pipeline. Code and model will be
released at https://github.com/magic-research/Sa2VA.
