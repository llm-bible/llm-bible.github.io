---
layout: publication
title: Unsupervised Vision-and-language Pre-training Via Retrieval-based Multi-granular
  Alignment
authors: Mingyang Zhou et al.
conference: Arxiv
year: 2022
citations: 18
bibkey: zhou2022unsupervised
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.00242'}]
tags: [Pre-Training, Multimodal Models]
---
Vision-and-Language (V+L) pre-training models have achieved tremendous
success in recent years on various multi-modal benchmarks. However, the
majority of existing models require pre-training on a large set of parallel
image-text data, which is costly to collect, compared to image-only or
text-only data. In this paper, we explore unsupervised Vision-and-Language
pre-training (UVLP) to learn the cross-modal representation from non-parallel
image and text datasets. We found two key factors that lead to good
unsupervised V+L pre-training without parallel data: (i) joint image-and-text
input (ii) overall image-text alignment (even for non-parallel data).
Accordingly, we propose a novel unsupervised V+L pre-training curriculum for
non-parallel texts and images. We first construct a weakly aligned image-text
corpus via a retrieval-based approach, then apply a set of multi-granular
alignment pre-training tasks, including region-to-tag, region-to-phrase, and
image-to-sentence alignment, to bridge the gap between the two modalities. A
comprehensive ablation study shows each granularity is helpful to learn a
stronger pre-trained model. We adapt our pre-trained model to a set of V+L
downstream tasks, including VQA, NLVR2, Visual Entailment, and RefCOCO+. Our
model achieves the state-of-art performance in all these tasks under the
unsupervised setting.