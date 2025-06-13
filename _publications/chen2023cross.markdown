---
layout: publication
title: 'Medprompt: Cross-modal Prompting For Multi-task Medical Image Translation'
authors: Xuhang Chen, Chi-man Pun, Shuqiang Wang
conference: "Arxiv"
year: 2023
bibkey: chen2023cross
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.02663'}
tags: ['Transformer', 'Tools', 'Model Architecture', 'Merging', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Cross-modal medical image translation is an essential task for synthesizing
missing modality data for clinical diagnosis. However, current learning-based
techniques have limitations in capturing cross-modal and global features,
restricting their suitability to specific pairs of modalities. This lack of
versatility undermines their practical usefulness, particularly considering
that the missing modality may vary for different cases. In this study, we
present MedPrompt, a multi-task framework that efficiently translates different
modalities. Specifically, we propose the Self-adaptive Prompt Block, which
dynamically guides the translation network towards distinct modalities. Within
this framework, we introduce the Prompt Extraction Block and the Prompt Fusion
Block to efficiently encode the cross-modal prompt. To enhance the extraction
of global features across diverse modalities, we incorporate the Transformer
model. Extensive experimental results involving five datasets and four pairs of
modalities demonstrate that our proposed model achieves state-of-the-art visual
quality and exhibits excellent generalization capability.
