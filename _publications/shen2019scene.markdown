---
layout: publication
title: 'Scene-based Factored Attention For Image Captioning'
authors: Chen Shen, Rongrong Ji, Fuhai Chen, Xiaoshuai Sun, Xiangming Li
conference: "Arxiv"
year: 2019
bibkey: shen2019scene
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1908.02632'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Tools', 'Ethics and Bias']
---
Image captioning has attracted ever-increasing research attention in the
multimedia community. To this end, most cutting-edge works rely on an
encoder-decoder framework with attention mechanisms, which have achieved
remarkable progress. However, such a framework does not consider scene concepts
to attend visual information, which leads to sentence bias in caption
generation and defects the performance correspondingly. We argue that such
scene concepts capture higher-level visual semantics and serve as an important
cue in describing images. In this paper, we propose a novel scene-based
factored attention module for image captioning. Specifically, the proposed
module first embeds the scene concepts into factored weights explicitly and
attends the visual information extracted from the input image. Then, an
adaptive LSTM is used to generate captions for specific scene types.
Experimental results on Microsoft COCO benchmark show that the proposed
scene-based attention module improves model performance a lot, which
outperforms the state-of-the-art approaches under various evaluation metrics.
