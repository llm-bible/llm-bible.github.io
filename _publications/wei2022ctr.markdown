---
layout: publication
title: 'CREATER: Ctr-driven Advertising Text Generation With Controlled Pre-training And Contrastive Fine-tuning'
authors: Penghui Wei, Xuanhua Yang, Shaoguo Liu, Liang Wang, Bo Zheng
conference: "Arxiv"
year: 2022
bibkey: wei2022ctr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.08943"}
tags: ['Training Techniques', 'Tools', 'Language Modeling', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
This paper focuses on automatically generating the text of an ad, and the
goal is that the generated text can capture user interest for achieving higher
click-through rate (CTR). We propose CREATER, a CTR-driven advertising text
generation approach, to generate ad texts based on high-quality user reviews.
To incorporate CTR objective, our model learns from online A/B test data with
contrastive learning, which encourages the model to generate ad texts that
obtain higher CTR. To alleviate the low-resource issue, we design a customized
self-supervised objective reducing the gap between pre-training and
fine-tuning. Experiments on industrial datasets show that CREATER significantly
outperforms current approaches. It has been deployed online in a leading
advertising platform and brings uplift on core online metrics.
