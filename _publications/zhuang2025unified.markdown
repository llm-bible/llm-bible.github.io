---
layout: publication
title: 'VARGPT: Unified Understanding And Generation In A Visual Autoregressive Multimodal Large Language Model'
authors: Xianwei Zhuang, Yuxin Xie, Yufan Deng, Liming Liang, Jinghan Ru, Yuguo Yin, Yuexian Zou
conference: "Arxiv"
year: 2025
bibkey: zhuang2025unified
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.12327'}
tags: ['Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Multimodal Models', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
We present VARGPT, a novel multimodal large language model (MLLM) that
unifies visual understanding and generation within a single autoregressive
framework. VARGPT employs a next-token prediction paradigm for visual
understanding and a next-scale prediction paradigm for visual autoregressive
generation. VARGPT innovatively extends the LLaVA architecture, achieving
efficient scale-wise autoregressive visual generation within MLLMs while
seamlessly accommodating mixed-modal input and output within a single model
framework. Our VARGPT undergoes a three-stage unified training process on
specially curated datasets, comprising a pre-training phase and two mixed
visual instruction-tuning phases. The unified training strategy are designed to
achieve alignment between visual and textual features, enhance instruction
following for both understanding and generation, and improve visual generation
quality, respectively. Despite its LLAVA-based architecture for multimodel
understanding, VARGPT significantly outperforms LLaVA-1.5 across various
vision-centric benchmarks, such as visual question-answering and reasoning
tasks. Notably, VARGPT naturally supports capabilities in autoregressive visual
generation and instruction-to-image synthesis, showcasing its versatility in
both visual understanding and generation tasks. Project page is at:
\url\{https://vargpt-1.github.io/\}
