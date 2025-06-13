---
layout: publication
title: 'LASER: Tuning-free Llm-driven Attention Control For Efficient Text-conditioned Image-to-animation'
authors: Haoyu Zheng, Wenqiao Zhang, Yaoke Wang, Juncheng Li, Zheqi Lv, Xin Min, Mengze Li, Dongping Zhang, Siliang Tang, Yueting Zhuang
conference: "Arxiv"
year: 2024
bibkey: zheng2024tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.13558"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
Revolutionary advancements in text-to-image models have unlocked new
dimensions for sophisticated content creation, such as text-conditioned image
editing, enabling the modification of existing images based on textual
guidance. This capability allows for the generation of diverse images that
convey highly complex visual concepts. However, existing methods primarily
focus on generating new images from text-image pairs and struggle to produce
fine-grained animations from existing images and textual guidance without
fine-tuning. In this paper, we introduce LASER, a tuning-free LLM-driven
attention control framework that follows a progressive process: LLM planning,
feature-attention injection, and stable animation generation. LASER leverages a
large language model (LLM) to refine general descriptions into fine-grained
prompts, guiding pre-trained text-to-image models to generate aligned keyframes
with subtle variations. The LLM also generates control signals for feature and
attention injections, enabling seamless text-guided image morphing for various
transformations without additional fine-tuning. By using the same initial noise
inversion from the input image, LASER receives LLM-controlled injections during
denoising and leverages interpolated text embeddings to produce a series of
coherent animation frames. We propose a Text-conditioned Image-to-Animation
Benchmark to validate the effectiveness and efficacy of LASER. Extensive
experiments demonstrate that LASER achieves impressive results in consistent
and efficient animation generation, establishing it as a powerful tool for
producing detailed animations and opening new avenues in digital content
creation.
