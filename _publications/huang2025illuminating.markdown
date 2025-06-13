---
layout: publication
title: 'ILLUME+: Illuminating Unified MLLM With Dual Visual Tokenization And Diffusion Refinement'
authors: Runhui Huang, Chunwei Wang, Junwei Yang, Guansong Lu, Yunlong Yuan, Jianhua Han, Lu Hou, Wei Zhang, Lanqing Hong, Hengshuang Zhao, Hang Xu
conference: "Arxiv"
year: 2025
bibkey: huang2025illuminating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01934'}
  - {name: "Code", url: 'https://illume-unified-mllm.github.io/'}
tags: ['Has Code', 'RAG', 'Applications', 'Training Techniques', 'Merging', 'Multimodal Models', 'Reinforcement Learning', 'Tokenization']
---
We present ILLUME+ that leverages dual visual tokenization and a diffusion
decoder to improve both deep semantic understanding and high-fidelity image
generation. Existing unified models have struggled to simultaneously handle the
three fundamental capabilities in a unified model: understanding, generation,
and editing. Models like Chameleon and EMU3 utilize VQGAN for image
discretization, due to the lack of deep semantic interaction, they lag behind
specialist models like LLaVA in visual understanding tasks. To mitigate this,
LaViT and ILLUME employ semantic encoders for tokenization, but they struggle
with image editing due to poor texture preservation. Meanwhile, Janus series
decouples the input and output image representation, limiting their abilities
to seamlessly handle interleaved image-text understanding and generation. In
contrast, ILLUME+ introduces a unified dual visual tokenizer, DualViTok, which
preserves both fine-grained textures and text-aligned semantics while enabling
a coarse-to-fine image representation strategy for multimodal understanding and
generation. Additionally, we employ a diffusion model as the image detokenizer
for enhanced generation quality and efficient super-resolution. ILLUME+ follows
a continuous-input, discrete-output scheme within the unified MLLM and adopts a
progressive training procedure that supports dynamic resolution across the
vision tokenizer, MLLM, and diffusion decoder. This design allows for flexible
and efficient context-aware image editing and generation across diverse tasks.
ILLUME+ (3B) exhibits competitive performance against existing unified MLLMs
and specialized models across multimodal understanding, generation, and editing
benchmarks. With its strong performance, ILLUME+ provides a scalable and
versatile foundation for future multimodal applications. Project Page:
https://illume-unified-mllm.github.io/.
