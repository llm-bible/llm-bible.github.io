---
layout: publication
title: 'Expediting Contrastive Language-image Pretraining Via Self-distilled Encoders'
authors: Bumsoo Kim, Jinhyung Kim, Yeonsik Jo, Seung Hwan Kim
conference: "Arxiv"
year: 2023
bibkey: kim2023expediting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12659"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Tools', 'Distillation', 'Pretraining Methods']
---
Recent advances in vision language pretraining (VLP) have been largely
attributed to the large-scale data collected from the web. However, uncurated
dataset contains weakly correlated image-text pairs, causing data inefficiency.
To address the issue, knowledge distillation have been explored at the expense
of extra image and text momentum encoders to generate teaching signals for
misaligned image-text pairs. In this paper, our goal is to resolve the
misalignment problem with an efficient distillation framework. To this end, we
propose ECLIPSE: Expediting Contrastive Language-Image Pretraining with
Self-distilled Encoders. ECLIPSE features a distinctive distillation
architecture wherein a shared text encoder is utilized between an online image
encoder and a momentum image encoder. This strategic design choice enables the
distillation to operate within a unified projected space of text embedding,
resulting in better performance. Based on the unified text embedding space,
ECLIPSE compensates for the additional computational cost of the momentum image
encoder by expediting the online image encoder. Through our extensive
experiments, we validate that there is a sweet spot between expedition and
distillation where the partial view from the expedited online image encoder
interacts complementarily with the momentum teacher. As a result, ECLIPSE
outperforms its counterparts while achieving substantial acceleration in
inference speed.
