---
layout: publication
title: 'Genesistex2: Stable, Consistent And High-quality Text-to-texture Generation'
authors: Jiawei Lu, Yingpeng Zhang, Zengjun Zhao, He Wang, Kun Zhou, Tianjia Shao
conference: "Arxiv"
year: 2024
bibkey: lu2024consistent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18401"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Attention Mechanism']
---
Large-scale text-guided image diffusion models have shown astonishing results
in text-to-image (T2I) generation. However, applying these models to synthesize
textures for 3D geometries remains challenging due to the domain gap between 2D
images and textures on a 3D surface. Early works that used a
projecting-and-inpainting approach managed to preserve generation diversity but
often resulted in noticeable artifacts and style inconsistencies. While recent
methods have attempted to address these inconsistencies, they often introduce
other issues, such as blurring, over-saturation, or over-smoothing. To overcome
these challenges, we propose a novel text-to-texture synthesis framework that
leverages pretrained diffusion models. We first introduce a local attention
reweighing mechanism in the self-attention layers to guide the model in
concentrating on spatial-correlated patches across different views, thereby
enhancing local details while preserving cross-view consistency. Additionally,
we propose a novel latent space merge pipeline, which further ensures
consistency across different viewpoints without sacrificing too much diversity.
Our method significantly outperforms existing state-of-the-art techniques
regarding texture consistency and visual quality, while delivering results much
faster than distillation-based methods. Importantly, our framework does not
require additional training or fine-tuning, making it highly adaptable to a
wide range of models available on public platforms.
