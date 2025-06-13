---
layout: publication
title: 'Tc-llava: Rethinking The Transfer From Image To Video Understanding With Temporal Considerations'
authors: Mingze Gao, Jingyu Liu, Mingda Li, Jiangtao Xie, Qingbin Liu, Bo Zhao, Xi Chen, Hui Xiong
conference: "Arxiv"
year: 2024
bibkey: gao2024tc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03206"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Multimodal Large Language Models (MLLMs) have significantly improved
performance across various image-language applications. Recently, there has
been a growing interest in adapting image pre-trained MLLMs for video-related
tasks. However, most efforts concentrate on enhancing the vision encoder and
projector components, while the core part, Large Language Models (LLMs),
remains comparatively under-explored. In this paper, we propose two strategies
to enhance the model's capability in video understanding tasks by improving
inter-layer attention computation in LLMs. Specifically, the first approach
focuses on the enhancement of Rotary Position Embedding (RoPE) with
Temporal-Aware Dual RoPE, which introduces temporal position information to
strengthen the MLLM's temporal modeling capabilities while preserving the
relative position relationships of both visual and text tokens. The second
approach involves enhancing the Attention Mask with the Frame-wise Block Causal
Attention Mask, a simple yet effective method that broadens visual token
interactions within and across video frames while maintaining the causal
inference mechanism. Based on these proposed methods, we adapt LLaVA for video
understanding tasks, naming it Temporal-Considered LLaVA (TC-LLaVA). Our
TC-LLaVA achieves new state-of-the-art performance across various video
understanding benchmarks with only supervised fine-tuning (SFT) on
video-related datasets.
