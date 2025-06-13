---
layout: publication
title: 'The Scalability Of Simplicity: Empirical Analysis Of Vision-language Learning With A Single Transformer'
authors: Weixian Lei, Jiacong Wang, Haochen Wang, Xiangtai Li, Jun Hao Liew, Jiashi Feng, Zilong Huang
conference: "Arxiv"
year: 2025
bibkey: lei2025scalability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10462"}
  - {name: "Code", url: "https://github.com/bytedance/SAIL"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Has Code', 'Attention Mechanism']
---
This paper introduces SAIL, a single transformer unified multimodal large
language model (MLLM) that integrates raw pixel encoding and language decoding
within a singular architecture. Unlike existing modular MLLMs, which rely on a
pre-trained vision transformer (ViT), SAIL eliminates the need for a separate
vision encoder, presenting a more minimalist architecture design. Instead of
introducing novel architectural components, SAIL adapts mix-attention
mechanisms and multimodal positional encodings to better align with the
distinct characteristics of visual and textual modalities. We systematically
compare SAIL's properties-including scalability, cross-modal information flow
patterns, and visual representation capabilities-with those of modular MLLMs.
By scaling both training data and model size, SAIL achieves performance
comparable to modular MLLMs. Notably, the removal of pretrained ViT components
enhances SAIL's scalability and results in significantly different cross-modal
information flow patterns. Moreover, SAIL demonstrates strong visual
representation capabilities, achieving results on par with ViT-22B in vision
tasks such as semantic segmentation. Code and models are available at
https://github.com/bytedance/SAIL.
