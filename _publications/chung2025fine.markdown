---
layout: publication
title: 'Fine-tuning Visual Autoregressive Models For Subject-driven Generation'
authors: Jiwoo Chung, Sangeek Hyun, Hyunjun Kim, Eunseo Koh, Minkyu Lee, Jae-pil Heo
conference: "Arxiv"
year: 2025
bibkey: chung2025fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02612"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Recent advances in text-to-image generative models have enabled numerous
practical applications, including subject-driven generation, which fine-tunes
pretrained models to capture subject semantics from only a few examples. While
diffusion-based models produce high-quality images, their extensive denoising
steps result in significant computational overhead, limiting real-world
applicability. Visual autoregressive~(VAR) models, which predict next-scale
tokens rather than spatially adjacent ones, offer significantly faster
inference suitable for practical deployment. In this paper, we propose the
first VAR-based approach for subject-driven generation. However, na\"\{\i\}ve
fine-tuning VAR leads to computational overhead, language drift, and reduced
diversity. To address these challenges, we introduce selective layer tuning to
reduce complexity and prior distillation to mitigate language drift.
Additionally, we found that the early stages have a greater influence on the
generation of subject than the latter stages, which merely synthesize local
details. Based on this finding, we propose scale-wise weighted tuning, which
prioritizes coarser resolutions for promoting the model to focus on the
subject-relevant information instead of local details. Extensive experiments
validate that our method significantly outperforms diffusion-based baselines
across various metrics and demonstrates its practical usage.
