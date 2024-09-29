---
layout: publication
title: "Lumina-mgpt: Illuminate Flexible Photorealistic Text-to-image Generation With Multimodal Generative Pretraining"
authors: Liu Dongyang, Zhao Shitian, Zhuo Le, Lin Weifeng, Qiao Yu, Li Hongsheng, Gao Peng
conference: "Arxiv"
year: 2024
bibkey: liu2024lumina
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02657"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
We present Lumina-mGPT a family of multimodal autoregressive models capable of various vision and language tasks particularly excelling in generating flexible photorealistic images from text descriptions. Unlike existing autoregressive image generation approaches Lumina-mGPT employs a pretrained decoder-only transformer as a unified framework for modeling multimodal token sequences. Our key insight is that a simple decoder-only transformer with multimodal Generative PreTraining (mGPT) utilizing the next-token prediction objective on massive interleaved text-image sequences can learn broad and general multimodal capabilities thereby illuminating photorealistic text-to-image generation. Building on these pretrained models we propose Flexible Progressive Supervised Finetuning (FP-SFT) on high-quality image-text pairs to fully unlock their potential for high-aesthetic image synthesis at any resolution while maintaining their general multimodal capabilities. Furthermore we introduce Ominiponent Supervised Finetuning (Omni-SFT) transforming Lumina-mGPT into a foundation model that seamlessly achieves omnipotent task unification. The resulting model demonstrates versatile multimodal capabilities including visual generation tasks like flexible text-to-image generation and controllable generation visual recognition tasks like segmentation and depth estimation and vision-language tasks like multiturn visual question answering. Additionally we analyze the differences and similarities between diffusion-based and autoregressive methods in a direct comparison.
