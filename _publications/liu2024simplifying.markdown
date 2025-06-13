---
layout: publication
title: 'Simplifying CLIP: Unleashing The Power Of Large-scale Models On Consumer-level Computers'
authors: Hongbo Liu
conference: "Arxiv"
year: 2024
bibkey: liu2024simplifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.14789'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Pre-Training', 'Pretraining Methods']
---
Contrastive Language-Image Pre-training (CLIP) has attracted a surge of
attention for its superior zero-shot performance and excellent transferability
to downstream tasks. However, training such large-scale models usually requires
substantial computation and storage, which poses barriers for general users
with consumer-level computers. Motivated by this observation, in this paper we
investigate how to achieve competitive performance on only one Nvidia RTX3090
GPU and with one terabyte for storing dataset. On one hand, we simplify the
transformer block structure and combine Weight Inheritance with multi-stage
Knowledge Distillation (WIKD), thereby reducing the parameters and improving
the inference speed during training along with deployment. On the other hand,
confronted with the convergence challenge posed by small dataset, we generate
synthetic captions for each sample as data augmentation, and devise a novel
Pair Matching (PM) loss to fully exploit the distinguishment among positive and
negative image-text pairs. Extensive experiments demonstrate that our model can
achieve a new state-of-the-art datascale-parameter-accuracy tradeoff, which
could further popularize the CLIP model in the related research community.
