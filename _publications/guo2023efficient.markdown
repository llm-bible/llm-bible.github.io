---
layout: publication
title: ELIP Efficient Language45;image Pre45;training With Fewer Vision Tokens
authors: Guo Yangyang, Zhang Haoyu, Wong Yongkang, Nie Liqiang, Kankanhalli Mohan
conference: "Arxiv"
year: 2023
bibkey: guo2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16738"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Pruning', 'RAG', 'Training Techniques']
---
Learning a versatile language45;image model is computationally prohibitive under a limited computing budget. This paper delves into the emph123;efficient language45;image pre45;training125; an area that has received relatively little attention despite its importance in reducing computational cost and footprint. To that end we propose a vision token pruning and merging method ELIP to remove less influential tokens based on the supervision of language outputs. Our method is designed with several strengths such as being computation45;efficient memory45;efficient and trainable45;parameter45;free and is distinguished from previous vision45;only token pruning approaches by its alignment with task objectives. We implement this method in a progressively pruning manner using several sequential blocks. To evaluate its generalization performance we apply ELIP to three commonly used language45;image pre45;training models and utilize public image45;caption pairs with 4M images for pre45;training. Our experiments demonstrate that with the removal of ~3037; vision tokens across 12 ViT layers ELIP maintains significantly comparable performance with baselines (sim0.32 accuracy drop on average) over various downstream tasks including cross45;modal retrieval VQA image captioning emph123;etc125;. In addition the spared GPU resources by our ELIP allow us to scale up with larger batch sizes thereby accelerating model pre45;training and even sometimes enhancing downstream model performance.
