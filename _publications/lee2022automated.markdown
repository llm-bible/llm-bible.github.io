---
layout: publication
title: Dialogcc An Automated Pipeline For Creating High-quality Multi-modal Dialogue Dataset
authors: Lee Young-jun, Ko Byungsoo, Kim Han-gyu, Hyeon Jonghwan, Choi Ho-jin
conference: "Arxiv"
year: 2022
bibkey: lee2022automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.04119"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Training Techniques']
---
As sharing images in an instant message is a crucial factor there has been active research on learning an image-text multi-modal dialogue models. However training a well-generalized multi-modal dialogue model remains challenging due to the low quality and limited diversity of images per dialogue in existing multi-modal dialogue datasets. In this paper we propose an automated pipeline to construct a multi-modal dialogue dataset ensuring both dialogue quality and image diversity without requiring minimum human effort. In our pipeline to guarantee the coherence between images and dialogue we prompt GPT-4 to infer potential image-sharing moments - specifically the utterance speaker rationale and image description. Furthermore we leverage CLIP similarity to maintain consistency between aligned multiple images to the utterance. Through this pipeline we introduce DialogCC a high-quality and diverse multi-modal dialogue dataset that surpasses existing datasets in terms of quality and diversity in human evaluation. Our comprehensive experiments highlight that when multi-modal dialogue models are trained using our dataset their generalization performance on unseen dialogue datasets is significantly enhanced. We make our source code and dataset publicly available.
