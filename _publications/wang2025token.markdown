---
layout: publication
title: 'TMCIR: Token Merge Benefits Composed Image Retrieval'
authors: Chaoyang Wang, Zeyu Zhang, Long Teng, Zijun Li, Shichao Kan
conference: "Arxiv"
year: 2025
bibkey: wang2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10995"}
tags: ['Tools', 'Ethics and Bias', 'Merging', 'Reinforcement Learning', 'Pretraining Methods', 'Multimodal Models']
---
Composed Image Retrieval (CIR) retrieves target images using a multi-modal
query that combines a reference image with text describing desired
modifications. The primary challenge is effectively fusing this visual and
textual information. Current cross-modal feature fusion approaches for CIR
exhibit an inherent bias in intention interpretation. These methods tend to
disproportionately emphasize either the reference image features
(visual-dominant fusion) or the textual modification intent (text-dominant
fusion through image-to-text conversion). Such an imbalanced representation
often fails to accurately capture and reflect the actual search intent of the
user in the retrieval results. To address this challenge, we propose TMCIR, a
novel framework that advances composed image retrieval through two key
innovations: 1) Intent-Aware Cross-Modal Alignment. We first fine-tune CLIP
encoders contrastively using intent-reflecting pseudo-target images,
synthesized from reference images and textual descriptions via a diffusion
model. This step enhances the encoder ability of text to capture nuanced
intents in textual descriptions. 2) Adaptive Token Fusion. We further fine-tune
all encoders contrastively by comparing adaptive token-fusion features with the
target image. This mechanism dynamically balances visual and textual
representations within the contrastive learning pipeline, optimizing the
composed feature for retrieval. Extensive experiments on Fashion-IQ and CIRR
datasets demonstrate that TMCIR significantly outperforms state-of-the-art
methods, particularly in capturing nuanced user intent.
