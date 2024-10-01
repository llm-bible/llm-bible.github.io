---
layout: publication
title: 'Difflora: Generating Personalized Low-rank Adaptation Weights With Diffusion'
authors: Wu Yujia, Shi Yiming, Wei Jiwei, Sun Chengwei, Zhou Yuyang, Yang Yang, Shen Heng Tao
conference: "Arxiv"
year: 2024
bibkey: wu2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06740"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Personalized text-to-image generation has gained significant attention for its capability to generate high-fidelity portraits of specific identities conditioned on user-defined prompts. Existing methods typically involve test-time fine-tuning or instead incorporating an additional pre-trained branch. However, these approaches struggle to simultaneously address the demands of efficiency, identity fidelity, and preserving the model's original generative capabilities. In this paper, we propose DiffLoRA, a novel approach that leverages diffusion models as a hypernetwork to predict personalized low-rank adaptation (LoRA) weights based on the reference images. By integrating these LoRA weights into the text-to-image model, DiffLoRA achieves personalization during inference without further training. Additionally, we propose an identity-oriented LoRA weight construction pipeline to facilitate the training of DiffLoRA. By utilizing the dataset produced by this pipeline, our DiffLoRA consistently generates high-performance and accurate LoRA weights. Extensive evaluations demonstrate the effectiveness of our method, achieving both time efficiency and maintaining identity fidelity throughout the personalization process.
