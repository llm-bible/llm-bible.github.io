---
layout: publication
title: 'CLAP: Isolating Content From Style Through Contrastive Learning With Augmented Prompts'
authors: Cai Yichao, Liu Yuhang, Zhang Zhen, Shi Javen Qinfeng
conference: "Arxiv"
year: 2023
bibkey: cai2023isolating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16445"}
tags: ['Attention Mechanism', 'Few Shot', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Security']
---
Contrastive vision-language models such as CLIP have garnered considerable attention for various dowmsteam tasks mainly due to the remarkable ability of the learned features for generalization. However the features they learned often blend content and style information which somewhat limits their generalization capabilities under distribution shifts. To address this limitation we adopt a causal generative perspective for multimodal data and propose contrastive learning with data augmentation to disentangle content features from the original representations. To achieve this we begin with exploring image augmentation techniques and develop a method to seamlessly integrate them into pre-trained CLIP-like models to extract pure content features. Taking a step further recognizing the inherent semantic richness and logical structure of text data we explore the use of text augmentation to isolate latent content from style features. This enables CLIP-like models encoders to concentrate on latent content information refining the learned representations by pre-trained CLIP-like models. Our extensive experiments across diverse datasets demonstrate significant improvements in zero-shot and few-shot classification tasks alongside enhanced robustness to various perturbations. These results underscore the effectiveness of our proposed methods in refining vision-language representations and advancing the state-of-the-art in multimodal learning.
