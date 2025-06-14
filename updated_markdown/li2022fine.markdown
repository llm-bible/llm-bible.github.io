---
layout: publication
title: 'Fine-grained Semantically Aligned Vision-language Pre-training'
authors: Juncheng Li et al.
conference: "Arxiv"
year: 2022
citations: 27
bibkey: li2022fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2208.02515'}
  - {name: "Code", url: 'https://github.com/YYJMJC/LOUPE'}
tags: ['Attention Mechanism', 'Has Code', 'Training Techniques', 'Tools', 'Model Architecture', 'Fine-Tuning', 'Multimodal Models', 'Pre-Training', 'Pretraining Methods']
---
Large-scale vision-language pre-training has shown impressive advances in a
wide range of downstream tasks. Existing methods mainly model the cross-modal
alignment by the similarity of the global representations of images and texts,
or advanced cross-modal attention upon image and text features. However, they
fail to explicitly learn the fine-grained semantic alignment between visual
regions and textual phrases, as only global image-text alignment information is
available. In this paper, we introduce LOUPE, a fine-grained semantically
aLigned visiOn-langUage PrE-training framework, which learns fine-grained
semantic alignment from the novel perspective of game-theoretic interactions.
To efficiently compute the game-theoretic interactions, we further propose an
uncertainty-aware neural Shapley interaction learning module. Experiments show
that LOUPE achieves state-of-the-art performance on a variety of
vision-language tasks. Furthermore, without any object-level human annotations
and fine-tuning, LOUPE achieves competitive performance on object detection and
visual grounding. More importantly, LOUPE opens a new promising direction of
learning fine-grained semantics from large-scale raw image-text pairs. The
repository of this work is at https://github.com/YYJMJC/LOUPE.
