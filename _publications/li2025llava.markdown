---
layout: publication
title: 'Llava-radz: Can Multimodal Large Language Models Effectively Tackle Zero-shot Radiology Recognition?'
authors: Bangyan Li, Wenxuan Huang, Yunhang Shen, Yeqiang Wang, Shaohui Lin, Jingzhong Lin, Ling You, Yinqi Zhang, Ke Li, Xing Sun, Yuling Sun
conference: "Arxiv"
year: 2025
bibkey: li2025llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07487"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning']
---
Recently, multimodal large models (MLLMs) have demonstrated exceptional
capabilities in visual understanding and reasoning across various
vision-language tasks. However, MLLMs usually perform poorly in zero-shot
medical disease recognition, as they do not fully exploit the captured features
and available medical knowledge. To address this challenge, we propose
LLaVA-RadZ, a simple yet effective framework for zero-shot medical disease
recognition. Specifically, we design an end-to-end training strategy, termed
Decoding-Side Feature Alignment Training (DFAT) to take advantage of the
characteristics of the MLLM decoder architecture and incorporate
modality-specific tokens tailored for different modalities, which effectively
utilizes image and text representations and facilitates robust cross-modal
alignment. Additionally, we introduce a Domain Knowledge Anchoring Module
(DKAM) to exploit the intrinsic medical knowledge of large models, which
mitigates the category semantic gap in image-text alignment. DKAM improves
category-level alignment, allowing for accurate disease recognition. Extensive
experiments on multiple benchmarks demonstrate that our LLaVA-RadZ
significantly outperforms traditional MLLMs in zero-shot disease recognition
and exhibits the state-of-the-art performance compared to the well-established
and highly-optimized CLIP-based approaches.
