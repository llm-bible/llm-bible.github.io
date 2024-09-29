---
layout: publication
title: Kangaroo&#58; A Powerful Video-language Model Supporting Long-context Video Input
authors: Liu Jiajun, Wang Yibing, Ma Hanghang, Wu Xiaoping, Ma Xiaoqi, Wei Xiaoming, Jiao Jianbin, Wu Enhua, Hu Jie
conference: "Arxiv"
year: 2024
bibkey: liu2024powerful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15542"}
tags: ['Multimodal Models', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Rapid advancements have been made in extending Large Language Models (LLMs) to Large Multi-modal Models (LMMs). However extending input modality of LLMs to video data remains a challenging endeavor especially for long videos. Due to insufficient access to large-scale high-quality video data and the excessive compression of visual features current methods exhibit limitations in effectively processing long videos. In this paper we introduce Kangaroo a powerful Video LMM aimed at addressing these challenges. Confronted with issue of inadequate training data we develop a data curation system to build a large-scale dataset with high-quality annotations for vision-language pre-training and instruction tuning. In addition we design a curriculum training pipeline with gradually increasing resolution and number of input frames to accommodate long videos. Evaluation results demonstrate that with 8B parameters Kangaroo achieves state-of-the-art performance across a variety of video understanding benchmarks while exhibiting competitive results on others. Particularly on benchmarks specialized for long videos Kangaroo excels some larger models with over 10B parameters and proprietary models.
