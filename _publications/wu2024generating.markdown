---
layout: publication
title: Difflora Generating Personalized Low45;rank Adaptation Weights With Diffusion
authors: Wu Yujia, Shi Yiming, Wei Jiwei, Sun Chengwei, Zhou Yuyang, Yang Yang, Shen Heng Tao
conference: "Arxiv"
year: 2024
bibkey: wu2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06740"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Personalized text45;to45;image generation has gained significant attention for its capability to generate high45;fidelity portraits of specific identities conditioned on user45;defined prompts. Existing methods typically involve test45;time fine45;tuning or instead incorporating an additional pre45;trained branch. However these approaches struggle to simultaneously address the demands of efficiency identity fidelity and preserving the models original generative capabilities. In this paper we propose DiffLoRA a novel approach that leverages diffusion models as a hypernetwork to predict personalized low45;rank adaptation (LoRA) weights based on the reference images. By integrating these LoRA weights into the text45;to45;image model DiffLoRA achieves personalization during inference without further training. Additionally we propose an identity45;oriented LoRA weight construction pipeline to facilitate the training of DiffLoRA. By utilizing the dataset produced by this pipeline our DiffLoRA consistently generates high45;performance and accurate LoRA weights. Extensive evaluations demonstrate the effectiveness of our method achieving both time efficiency and maintaining identity fidelity throughout the personalization process.
