---
layout: publication
title: 'Vision As Lora'
authors: Han Wang, Yongjie Ye, Bingru Li, Yuxiang Nie, Jinghui Lu, Jingqun Tang, Yanjie Wang, Can Huang
conference: "Arxiv"
year: 2025
bibkey: wang2025vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20680"}
  - {name: "Code", url: "https://github.com/Hon-Wong/VoRA"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'Fine-Tuning', 'Has Code', 'Pre-Training', 'Attention Mechanism']
---
We introduce Vision as LoRA (VoRA), a novel paradigm for transforming an LLM
into an MLLM. Unlike prevalent MLLM architectures that rely on external vision
modules for vision encoding, VoRA internalizes visual capabilities by
integrating vision-specific LoRA layers directly into the LLM. This design
allows the added parameters to be seamlessly merged into the LLM during
inference, eliminating structural complexity and minimizing computational
overhead. Moreover, inheriting the LLM's ability of handling flexible context,
VoRA can process inputs at arbitrary resolutions.
  To further strengthen VoRA's visual capabilities, we introduce a block-wise
distillation method that transfers visual priors from a pre-trained ViT into
the LoRA layers, effectively accelerating training by injecting visual
knowledge. Additionally, we apply bi-directional attention masks to better
capture the context information of an image. We successfully demonstrate that
with additional pre-training data, VoRA can perform comparably with
conventional encode-based MLLMs. All training data, codes, and model weights
will be released at https://github.com/Hon-Wong/VoRA.
