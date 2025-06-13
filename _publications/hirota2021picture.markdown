---
layout: publication
title: 'A Picture May Be Worth A Hundred Words For Visual Question Answering'
authors: Yusuke Hirota, Noa Garcia, Mayu Otani, Chenhui Chu, Yuta Nakashima, Ittetsu Taniguchi, Takao Onoye
conference: "Arxiv"
year: 2021
bibkey: hirota2021picture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2106.13445'}
tags: ['Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Ethics and Bias', 'Pretraining Methods']
---
How far can we go with textual representations for understanding pictures? In
image understanding, it is essential to use concise but detailed image
representations. Deep visual features extracted by vision models, such as
Faster R-CNN, are prevailing used in multiple tasks, and especially in visual
question answering (VQA). However, conventional deep visual features may
struggle to convey all the details in an image as we humans do. Meanwhile, with
recent language models' progress, descriptive text may be an alternative to
this problem. This paper delves into the effectiveness of textual
representations for image understanding in the specific context of VQA. We
propose to take description-question pairs as input, instead of deep visual
features, and fed them into a language-only Transformer model, simplifying the
process and the computational cost. We also experiment with data augmentation
techniques to increase the diversity in the training set and avoid learning
statistical bias. Extensive evaluations have shown that textual representations
require only about a hundred words to compete with deep visual features on both
VQA 2.0 and VQA-CP v2.
