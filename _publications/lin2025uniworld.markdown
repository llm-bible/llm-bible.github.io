---
layout: publication
title: 'Uniworld-v1: High-resolution Semantic Encoders For Unified Visual Understanding And Generation'
authors: Bin Lin, Zongjian Li, Xinhua Cheng, Yuwei Niu, Yang Ye, Xianyi He, Shenghai Yuan, Wangbo Yu, Shaodong Wang, Yunyang Ge, Yatian Pang, Li Yuan
conference: "Arxiv"
year: 2025
bibkey: lin2025uniworld
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03147"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Applications']
---
Although existing unified models achieve strong performance in vision-language understanding and text-to-image generation, they remain limited in addressing image perception and manipulation -- capabilities increasingly demanded in practical applications. Recently, OpenAI introduced the powerful GPT-4o-Image model, which showcases advanced capabilities in comprehensive image perception and manipulation, sparking widespread interest. Through carefully designed experiments, we observe that GPT-4o-Image likely relies on semantic encoders rather than VAEs for feature extraction, despite VAEs being commonly regarded as crucial for image manipulation tasks. Inspired by this insight, we propose UniWorld-V1, a unified generative framework built upon semantic features extracted from powerful multimodal large language models and contrastive semantic encoders. Using only 2.7M training data, UniWorld-V1 achieves impressive performance across diverse tasks, including image understanding, generation, manipulation, and perception. We fully open-source the UniWorld-V1 framework, including model weights, training and evaluation scripts, and datasets to promote reproducibility and further research.
