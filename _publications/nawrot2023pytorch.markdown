---
layout: publication
title: 'Nanot5: A Pytorch Framework For Pre-training And Fine-tuning T5-style Models With Limited Resources'
authors: Piotr Nawrot
conference: "Arxiv"
year: 2023
bibkey: nawrot2023pytorch
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.02373'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
State-of-the-art language models like T5 have revolutionized the NLP
landscape, but their computational demands hinder a large portion of the
research community. To address this challenge, we present nanoT5, a
specially-optimized PyTorch framework for efficient pre-training and
fine-tuning of T5 models. Drawing on insights from optimizer differences and
prioritizing efficiency, nanoT5 allows a T5-Base model to be pre-trained on a
single GPU in just 16 hours, without any loss in performance. With the
introduction of this open-source framework, we hope to widen the accessibility
to language modelling research and cater to the community's demand for more
user-friendly T5 (Encoder-Decoder) implementations. We make our contributions,
including configurations, codebase, pre-training insights, and pre-trained
models, available to the public.
