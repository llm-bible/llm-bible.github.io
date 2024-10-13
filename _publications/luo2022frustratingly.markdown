---
layout: publication
title: 'A Frustratingly Simple Approach For End-to-end Image Captioning'
authors: Luo Ziyang, Xi Yadong, Zhang Rongsheng, Ma Jing
conference: "Arxiv"
year: 2022
bibkey: luo2022frustratingly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.12723"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Image Captioning is a fundamental task to join vision and language,
concerning about cross-modal understanding and text generation. Recent years
witness the emerging attention on image captioning. Most of existing works
follow a traditional two-stage training paradigm. Before training the
captioning models, an extra object detector is utilized to recognize the
objects in the image at first. However, they require sizeable datasets with
fine-grained object annotation for training the object detector, which is a
daunting task. In addition, the errors of the object detectors are easy to
propagate to the following captioning models, degenerating models' performance.
To alleviate such defects, we propose a frustratingly simple but highly
effective end-to-end image captioning framework, Visual Conditioned GPT
(VC-GPT), by connecting the pre-trained visual encoder (CLIP-ViT) and language
decoder (GPT2). Different from the vanilla connection method that directly
inserts the cross-attention modules into GPT2, we come up with a self-ensemble
cross-modal fusion mechanism that comprehensively considers both the single-
and cross-modal knowledge. As a result, we do not need extra object detectors
for model training. Experimental results conducted on three popular image
captioning benchmarks (MSCOCO, Flickr30k and NoCaps) demonstrate that our
VC-GPT achieves either the best or the second-best performance across all
evaluation metrics over extensive baseline systems.
