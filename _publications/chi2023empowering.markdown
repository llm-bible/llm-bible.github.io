---
layout: publication
title: M$^{2}$chat\: Empowering VLM For Multimodal LLM Interleaved Text-image Generation
authors: Chi Xiaowei, Zhang Rongyu, Jiang Zhengkai, Liu Yijiang, Wang Yatian, Qi Xingqun, Luo Wenhan, Gao Peng, Zhang Shanghang, Liu Qifeng, Guo Yike
conference: "Arxiv"
year: 2023
bibkey: chi2023empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17963"}
  - {name: "Code", url: "https://mattie-e.github.io/M2Chat.github.io"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While current LLM chatbots like GPT-4V bridge the gap between human instructions and visual representations to enable text-image generations they still lack efficient alignment methods for high-fidelity performance on multiple downstream tasks. In this paper we propose (textbf)M^2Chat a novel unified multimodal LLM framework for generating interleaved text-image conversation across various scenarios. Specifically we propose an M^3Adapter that efficiently integrates granular low-level visual information and high-level semantic features from multi-modality prompts. Upon the well-aligned fused feature M^3Adapter tailors a learnable gating strategy to balance the model creativity and consistency across various tasks adaptively. Moreover to further enhance the effectiveness of M^3Adapter while preserving the coherence of semantic context comprehension we introduce a two-stage M^3FT fine-tuning strategy. This strategy optimizes disjoint groups of parameters for image-text alignment and visual-instruction respectively. Extensive experiments demonstrate our M^2Chat surpasses state-of-the-art counterparts across diverse benchmarks showcasing its prowess in interleaving generation storytelling and multimodal dialogue systems. The demo and code are available at (red)https://mattie-e.github.io/M2Chat.github.io\}."
