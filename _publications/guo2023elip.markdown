---
layout: publication
title: ELIP Efficient Language-Image Pre-training with Fewer Vision Tokens
authors: Guo Yangyang, Zhang Haoyu, Wong Yongkang, Nie Liqiang, Kankanhalli Mohan
conference: "Arxiv"
year: 2023
bibkey: guo2023elip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16738"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pruning', 'RAG', 'Training Techniques']
---
Learning a versatile language-image model is computationally prohibitive under a limited computing budget. This paper delves into the emphefficient language-image pre-training an area that has received relatively little attention despite its importance in reducing computational cost and footprint. To that end we propose a vision token pruning and merging method ELIP to remove less influential tokens based on the supervision of language outputs. Our method is designed with several strengths such as being computation-efficient memory-efficient and trainable-parameter-free and is distinguished from previous vision-only token pruning approaches by its alignment with task objectives. We implement this method in a progressively pruning manner using several sequential blocks. To evaluate its generalization performance we apply ELIP to three commonly used language-image pre-training models and utilize public image-caption pairs with 4M images for pre-training. Our experiments demonstrate that with the removal of ~30 vision tokens across 12 ViT layers ELIP maintains significantly comparable performance with baselines (sim0.32 accuracy drop on average) over various downstream tasks including cross-modal retrieval VQA image captioning emphetc. In addition the spared GPU resources by our ELIP allow us to scale up with larger batch sizes thereby accelerating model pre-training and even sometimes enhancing downstream model performance.
