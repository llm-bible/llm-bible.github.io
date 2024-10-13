---
layout: publication
title: 'Noiseboost: Alleviating Hallucination With Noise Perturbation For Multimodal Large Language Models'
authors: Wu Kai, Jiang Boyuan, Jiang Zhengkai, He Qingdong, Luo Donghao, Wang Shengzhi, Liu Qingwen, Wang Chengjie
conference: "Arxiv"
year: 2024
bibkey: wu2024alleviating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20081"}
  - {name: "Code", url: "https://kaiwu5.github.io/noiseboost"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
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
