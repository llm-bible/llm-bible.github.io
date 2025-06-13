---
layout: publication
title: 'Muddit: Liberating Generation Beyond Text-to-image With A Unified Discrete Diffusion Model'
authors: Qingyu Shi, Jinbin Bai, Zhuoran Zhao, Wenhao Chai, Kaidong Yu, Jianzong Wu, Shuangyong Song, Yunhai Tong, Xiangtai Li, Xuelong Li, Shuicheng Yan
conference: "Arxiv"
year: 2025
bibkey: shi2025liberating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23606'}
tags: ['Language Modeling', 'Transformer', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Merging', 'Applications', 'Multimodal Models', 'Pretraining Methods']
---
Unified generation models aim to handle diverse tasks across modalities -- such as text generation, image generation, and vision-language reasoning -- within a single architecture and decoding paradigm. Autoregressive unified models suffer from slow inference due to sequential decoding, and non-autoregressive unified models suffer from weak generalization due to limited pretrained backbones. We introduce Muddit, a unified discrete diffusion transformer that enables fast and parallel generation across both text and image modalities. Unlike prior unified diffusion models trained from scratch, Muddit integrates strong visual priors from a pretrained text-to-image backbone with a lightweight text decoder, enabling flexible and high-quality multimodal generation under a unified architecture. Empirical results show that Muddit achieves competitive or superior performance compared to significantly larger autoregressive models in both quality and efficiency. The work highlights the potential of purely discrete diffusion, when equipped with strong visual priors, as a scalable and effective backbone for unified generation.
