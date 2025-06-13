---
layout: publication
title: 'Noiseboost: Alleviating Hallucination With Noise Perturbation For Multimodal Large Language Models'
authors: Kai Wu, Boyuan Jiang, Zhengkai Jiang, Qingdong He, Donghao Luo, Shengzhi Wang, Qingwen Liu, Chengjie Wang
conference: "Arxiv"
year: 2024
bibkey: wu2024alleviating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.20081'}
  - {name: "Code", url: 'https://kaiwu5.github.io/noiseboost'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Multimodal large language models (MLLMs) contribute a powerful mechanism to
understanding visual information building on large language models. However,
MLLMs are notorious for suffering from hallucinations, especially when
generating lengthy, detailed descriptions for images. Our analysis reveals that
hallucinations stem from the inherent summarization mechanism of large language
models, leading to excessive dependence on linguistic tokens while neglecting
vision information. In this paper, we propose NoiseBoost, a broadly applicable
and simple method for alleviating hallucinations for MLLMs through the
integration of noise feature perturbations. Noise perturbation acts as a
regularizer, facilitating a balanced distribution of attention weights among
visual and linguistic tokens. Despite its simplicity, NoiseBoost consistently
enhances the performance of MLLMs across common training strategies, including
supervised fine-tuning and reinforcement learning. Further, NoiseBoost
pioneerly enables semi-supervised learning for MLLMs, unleashing the power of
unlabeled data. Comprehensive experiments demonstrate that NoiseBoost improves
dense caption accuracy by 8.1% with human evaluation and achieves comparable
results with 50% of the data by mining unlabeled data. Code and models are
available at https://kaiwu5.github.io/noiseboost.
