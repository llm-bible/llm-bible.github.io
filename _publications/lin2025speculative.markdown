---
layout: publication
title: 'Speculative Decoding Reimagined For Multimodal Large Language Models'
authors: Luxi Lin, Zhihang Lin, Zhanpeng Zeng, Rongrong Ji
conference: "Arxiv"
year: 2025
bibkey: lin2025speculative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14260'}
  - {name: "Code", url: 'https://github.com/Lyn-Lucy/MSD'}
tags: ['Has Code', 'Language Modeling', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models']
---
This paper introduces Multimodal Speculative Decoding (MSD) to accelerate Multimodal Large Language Models (MLLMs) inference. Speculative decoding has been shown to accelerate Large Language Models (LLMs) without sacrificing accuracy. However, current speculative decoding methods for MLLMs fail to achieve the same speedup as they do for LLMs. To address this, we reimagine speculative decoding specifically for MLLMs. Our analysis of MLLM characteristics reveals two key design principles for MSD: (1) Text and visual tokens have fundamentally different characteristics and need to be processed separately during drafting. (2) Both language modeling ability and visual perception capability are crucial for the draft model. For the first principle, MSD decouples text and visual tokens in the draft model, allowing each to be handled based on its own characteristics. For the second principle, MSD uses a two-stage training strategy: In stage one, the draft model is trained on text-only instruction-tuning datasets to improve its language modeling ability. In stage two, MSD gradually introduces multimodal data to enhance the visual perception capability of the draft model. Experiments show that MSD boosts inference speed by up to \\(2.29\times\\) for LLaVA-1.5-7B and up to \\(2.46\times\\) for LLaVA-1.5-13B on multimodal benchmarks, demonstrating its effectiveness. Our code is available at https://github.com/Lyn-Lucy/MSD.
