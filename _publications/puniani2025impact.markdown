---
layout: publication
title: 'Impact Of Language Guidance: A Reproducibility Study'
authors: Cherish Puniani, Advika Sinha, Shree Singhi, Aayan Yadav
conference: "Arxiv"
year: 2025
bibkey: puniani2025impact
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08140'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods']
---
Modern deep-learning architectures need large amounts of data to produce
state-of-the-art results. Annotating such huge datasets is time-consuming,
expensive, and prone to human error. Recent advances in self-supervised
learning allow us to train huge models without explicit annotation. Contrastive
learning is a popular paradigm in self-supervised learning. Recent works like
SimCLR and CLIP rely on image augmentations or directly minimizing cross-modal
loss between image and text. Banani et al. (2023) propose to use language
guidance to sample view pairs. They claim that language enables better
conceptual similarity, eliminating the effects of visual variability. We
reproduce their experiments to verify their claims and find that their dataset,
RedCaps, contains low-quality captions. We use an off-the-shelf image
captioning model, BLIP-2, to replace the captions and improve performance, and
we also devise a new metric to evaluate the semantic capabilities of
self-supervised models based on interpretability methods.
