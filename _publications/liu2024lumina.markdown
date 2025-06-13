---
layout: publication
title: 'Lumina-mgpt: Illuminate Flexible Photorealistic Text-to-image Generation With Multimodal Generative Pretraining'
authors: Dongyang Liu, Shitian Zhao, Le Zhuo, Weifeng Lin, Yi Xin, Xinyue Li, Qi Qin, Yu Qiao, Hongsheng Li, Peng Gao
conference: "Arxiv"
year: 2024
bibkey: liu2024lumina
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02657"}
  - {name: "Code", url: "https://github.com/Alpha-VLLM/Lumina-mGPT"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Merging', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
We present Lumina-mGPT, a family of multimodal autoregressive models capable
of various vision and language tasks, particularly excelling in generating
flexible photorealistic images from text descriptions. By initializing from
multimodal Generative PreTraining (mGPT), we demonstrate that decoder-only
Autoregressive (AR) model can achieve image generation performance comparable
to modern diffusion models with high efficiency through Flexible Progressive
Supervised Fine-tuning (FP-SFT). Equipped with our proposed Unambiguous image
Representation (UniRep), Lumina-mGPT can flexibly generate high-quality images
of varying aspect ratios. Building on the strong image generation capabilities,
we further explore Ominiponent Supervised Fine-tuning (Omni-SFT), an initial
attempt to elevate Lumina-mGPT into a unified multi-modal generalist. The
resulting model demonstrates versatile multimodal capabilities, including
visual generation tasks like text-to-image/multiview generation and
controllable generation, visual recognition tasks like segmentation and depth
estimation, and vision-language tasks like multi-turn visual question
answering, showing the rosy potential of the technical direction. Codes and
checkpoints are available at https://github.com/Alpha-VLLM/Lumina-mGPT.
