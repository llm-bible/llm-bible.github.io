---
layout: publication
title: HiCLIP Contrastive Language-Image Pretraining with Hierarchy-aware Attention
authors: Geng Shijie, Yuan Jianbo, Tian Yu, Chen Yuxiao, Zhang Yongfeng
conference: "Arxiv"
year: 2023
bibkey: geng2023hiclip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.02995"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques']
---
The success of large-scale contrastive vision-language pretraining (CLIP) has benefited both visual recognition and multimodal content understanding. The concise design brings CLIP the advantage in inference efficiency against other vision-language models with heavier cross-attention fusion layers making it a popular choice for a wide spectrum of downstream tasks. However CLIP does not explicitly capture the hierarchical nature of high-level and fine-grained semantics conveyed in images and texts which is arguably critical to vision-language understanding and reasoning. To this end we equip both the visual and language branches in CLIP with hierarchy-aware attentions namely Hierarchy-aware CLIP (HiCLIP) to progressively discover semantic hierarchies layer-by-layer from both images and texts in an unsupervised manner. As a result such hierarchical aggregation significantly improves the cross-modal alignment. To demonstrate the advantages of HiCLIP we conduct qualitative analysis on its unsupervised hierarchy induction during inference as well as extensive quantitative experiments on both visual recognition and vision-language downstream tasks.
