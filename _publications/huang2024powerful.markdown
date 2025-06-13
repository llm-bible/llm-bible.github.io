---
layout: publication
title: 'LLM2CLIP: Powerful Language Model Unlocks Richer Visual Representation'
authors: Weiquan Huang, Aoqi Wu, Yifan Yang, Xufang Luo, Yuqing Yang, Liang Hu, Qi Dai, Chunyu Wang, Xiyang Dai, Dongdong Chen, Chong Luo, Lili Qiu
conference: "Arxiv"
year: 2024
bibkey: huang2024powerful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.04997"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
CLIP is a foundational multimodal model that aligns image and text features
into a shared representation space via contrastive learning on large-scale
image-text pairs. Its effectiveness primarily stems from the use of natural
language as rich supervision. Motivated by the remarkable advancements in large
language models (LLMs), this work explores how LLMs' superior text
understanding and extensive open-world knowledge can enhance CLIP's capability,
especially for processing longer and more complex image captions. We propose an
efficient post-training strategy that integrates LLMs into pretrained CLIP. To
address the challenge posed by the autoregressive nature of LLMs, we introduce
a caption-to-caption contrastive fine-tuning framework, significantly enhancing
the discriminative quality of LLM outputs. Extensive experiments demonstrate
that our approach outperforms LoRA-based methods, achieving nearly fourfold
faster training with superior performance. Furthermore, we validate substantial
improvements over state-of-the-art models such as CLIP, EVA02, and SigLip2
across various zero-shot multimodal retrieval tasks, cross-lingual retrieval
tasks, and multimodal language model pretraining.
