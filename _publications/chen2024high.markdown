---
layout: publication
title: 'High-resolution Image Synthesis Via Next-token Prediction'
authors: Dengsheng Chen, Jie Hu, Tiezhu Yue, Xiaoming Wei, Enhua Wu
conference: "Arxiv"
year: 2024
bibkey: chen2024high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14808"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'RAG', 'GPT', 'Pretraining Methods', 'Transformer']
---
Recently, autoregressive models have demonstrated remarkable performance in
class-conditional image generation. However, the application of next-token
prediction to high-resolution text-to-image generation remains largely
unexplored. In this paper, we introduce \textbf\{D-JEPA\\(\cdot\\)T2I\}, an
autoregressive model based on continuous tokens that incorporates innovations
in both architecture and training strategy to generate high-quality,
photorealistic images at arbitrary resolutions, up to 4K. Architecturally, we
adopt the denoising joint embedding predictive architecture (D-JEPA) while
leveraging a multimodal visual transformer to effectively integrate textual and
visual features. Additionally, we introduce flow matching loss alongside the
proposed Visual Rotary Positional Embedding (VoPE) to enable continuous
resolution learning. In terms of training strategy, we propose a data feedback
mechanism that dynamically adjusts the sampling procedure based on statistical
analysis and an online learning critic model. This encourages the model to move
beyond its comfort zone, reducing redundant training on well-mastered scenarios
and compelling it to address more challenging cases with suboptimal generation
quality. For the first time, we achieve state-of-the-art high-resolution image
synthesis via next-token prediction.
