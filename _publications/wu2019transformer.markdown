---
layout: publication
title: 'Transformer-based Cascaded Multimodal Speech Translation'
authors: Zixiu Wu, Ozan Caglayan, Julia Ive, Josiah Wang, Lucia Specia
conference: "Arxiv"
year: 2019
bibkey: wu2019transformer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1910.13215'}
tags: ['Attention Mechanism', 'Transformer', 'SLT', 'INTERSPEECH', 'Model Architecture', 'Applications', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
This paper describes the cascaded multimodal speech translation systems
developed by Imperial College London for the IWSLT 2019 evaluation campaign.
The architecture consists of an automatic speech recognition (ASR) system
followed by a Transformer-based multimodal machine translation (MMT) system.
While the ASR component is identical across the experiments, the MMT model
varies in terms of the way of integrating the visual context (simple
conditioning vs. attention), the type of visual features exploited (pooled,
convolutional, action categories) and the underlying architecture. For the
latter, we explore both the canonical transformer and its deliberation version
with additive and cascade variants which differ in how they integrate the
textual attention. Upon conducting extensive experiments, we found that (i) the
explored visual integration schemes often harm the translation performance for
the transformer and additive deliberation, but considerably improve the cascade
deliberation; (ii) the transformer and cascade deliberation integrate the
visual modality better than the additive deliberation, as shown by the
incongruence analysis.
