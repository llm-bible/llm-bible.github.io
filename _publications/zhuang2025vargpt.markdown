---
layout: publication
title: 'Vargpt-v1.1: Improve Visual Autoregressive Large Unified Model Via Iterative Instruction Tuning And Reinforcement Learning'
authors: Xianwei Zhuang, Yuxin Xie, Yufan Deng, Dongchao Yang, Liming Liang, Jinghan Ru, Yuguo Yin, Yuexian Zou
conference: "Arxiv"
year: 2025
bibkey: zhuang2025vargpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02949"}
  - {name: "Code", url: "https://github.com/VARGPT-family/VARGPT-v1.1"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Has Code']
---
In this work, we present VARGPT-v1.1, an advanced unified visual
autoregressive model that builds upon our previous framework VARGPT. The model
preserves the dual paradigm of next-token prediction for visual understanding
and next-scale generation for image synthesis. Specifically, VARGPT-v1.1
integrates: (1) a novel training strategy combining iterative visual
instruction tuning with reinforcement learning through Direct Preference
Optimization (DPO), (2) an expanded training corpus containing 8.3M
visual-generative instruction pairs, (3) an upgraded language model backbone
using Qwen2, (4) enhanced image generation resolution, and (5) emergent image
editing capabilities without architectural modifications. These advancements
enable VARGPT-v1.1 to achieve state-of-the-art performance in multimodal
understanding and text-to-image instruction-following tasks, demonstrating
significant improvements in both comprehension and generation metrics. Notably,
through visual instruction tuning, the model acquires image editing
functionality while maintaining architectural consistency with its predecessor,
revealing the potential for unified visual understanding, generation, and
editing. Our findings suggest that well-designed unified visual autoregressive
models can effectively adopt flexible training strategies from large language
models (LLMs), exhibiting promising scalability. The codebase and model weights
are publicly available at https://github.com/VARGPT-family/VARGPT-v1.1.
