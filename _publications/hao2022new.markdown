---
layout: publication
title: 'Mixgen: A New Multi-modal Data Augmentation'
authors: Xiaoshuai Hao et al.
conference: Arxiv
year: 2022
citations: 53
bibkey: hao2022new
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.08358'}]
tags: [Pre-Training, Efficiency and Optimization, Multimodal Models]
---
Data augmentation is a necessity to enhance data efficiency in deep learning.
For vision-language pre-training, data is only augmented either for images or
for text in previous works. In this paper, we present MixGen: a joint data
augmentation for vision-language representation learning to further improve
data efficiency. It generates new image-text pairs with semantic relationships
preserved by interpolating images and concatenating text. It's simple, and can
be plug-and-played into existing pipelines. We evaluate MixGen on four
architectures, including CLIP, ViLT, ALBEF and TCL, across five downstream
vision-language tasks to show its versatility and effectiveness. For example,
adding MixGen in ALBEF pre-training leads to absolute performance improvements
on downstream tasks: image-text retrieval (+6.2% on COCO fine-tuned and +5.3%
on Flicker30K zero-shot), visual grounding (+0.9% on RefCOCO+), visual
reasoning (+$0.9% on NLVR2), visual question answering (+0.3% on VQA2.0), and
visual entailment (+0.4% on SNLI-VE).