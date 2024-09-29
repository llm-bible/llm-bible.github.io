---
layout: publication
title: Pandora Towards General World Model With Natural Language Actions And Video States
authors: Xiang Jiannan, Liu Guangyi, Gu Yi, Gao Qiyue, Ning Yuting, Zha Yuheng, Feng Zeyu, Tao Tianhua, Hao Shibo, Shi Yemin, Liu Zhengzhong, Xing Eric P., Hu Zhiting
conference: "Arxiv"
year: 2024
bibkey: xiang2024pandora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09455"}
tags: ['GPT', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
World models simulate future states of the world in response to different actions. They facilitate interactive content creation and provides a foundation for grounded long-horizon reasoning. Current foundation models do not fully meet the capabilities of general world models large language models (LLMs) are constrained by their reliance on language modality and their limited understanding of the physical world while video models lack interactive action control over the world simulations. This paper makes a step towards building a general world model by introducing Pandora a hybrid autoregressive-diffusion model that simulates world states by generating videos and allows real-time control with free-text actions. Pandora achieves domain generality video consistency and controllability through large-scale pretraining and instruction tuning. Crucially Pandora bypasses the cost of training-from-scratch by integrating a pretrained LLM (7B) and a pretrained video model requiring only additional lightweight finetuning. We illustrate extensive outputs by Pandora across diverse domains (indoor/outdoor natural/urban human/robot 2D/3D etc.). The results indicate great potential of building stronger general world models with larger-scale training.
