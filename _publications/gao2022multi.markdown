---
layout: publication
title: 'MIST: Multi-modal Iterative Spatial-temporal Transformer For Long-form Video
  Question Answering'
authors: Difei Gao et al.
conference: Arxiv
year: 2022
citations: 44
bibkey: gao2022multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.09522'}]
tags: [Transformer, Pre-Training, Efficiency and Optimization, Interpretability and
    Explainability, Attention Mechanism, Model Architecture]
---
To build Video Question Answering (VideoQA) systems capable of assisting
humans in daily activities, seeking answers from long-form videos with diverse
and complex events is a must. Existing multi-modal VQA models achieve promising
performance on images or short video clips, especially with the recent success
of large-scale multi-modal pre-training. However, when extending these methods
to long-form videos, new challenges arise. On the one hand, using a dense video
sampling strategy is computationally prohibitive. On the other hand, methods
relying on sparse sampling struggle in scenarios where multi-event and
multi-granularity visual reasoning are required. In this work, we introduce a
new model named Multi-modal Iterative Spatial-temporal Transformer (MIST) to
better adapt pre-trained models for long-form VideoQA. Specifically, MIST
decomposes traditional dense spatial-temporal self-attention into cascaded
segment and region selection modules that adaptively select frames and image
regions that are closely relevant to the question itself. Visual concepts at
different granularities are then processed efficiently through an attention
module. In addition, MIST iteratively conducts selection and attention over
multiple layers to support reasoning over multiple events. The experimental
results on four VideoQA datasets, including AGQA, NExT-QA, STAR, and Env-QA,
show that MIST achieves state-of-the-art performance and is superior at
computation efficiency and interpretability.