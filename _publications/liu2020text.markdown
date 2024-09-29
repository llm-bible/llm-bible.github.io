---
layout: publication
title: TIME Text And Image Mutual45;translation Adversarial Networks
authors: Liu Bingchen, Song Kunpeng, Zhu Yizhe, De Melo Gerard, Elgammal Ahmed
conference: "Arxiv"
year: 2020
bibkey: liu2020text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.13192"}
tags: ['Model Architecture', 'Pretraining Methods', 'Security', 'Tools', 'Training Techniques', 'Transformer']
---
Focusing on text45;to45;image (T2I) generation we propose Text and Image Mutual45;Translation Adversarial Networks (TIME) a lightweight but effective model that jointly learns a T2I generator G and an image captioning discriminator D under the Generative Adversarial Network framework. While previous methods tackle the T2I problem as a uni45;directional task and use pre45;trained language models to enforce the image45;45;text consistency TIME requires neither extra modules nor pre45;training. We show that the performance of G can be boosted substantially by training it jointly with D as a language model. Specifically we adopt Transformers to model the cross45;modal connections between the image features and word embeddings and design an annealing conditional hinge loss that dynamically balances the adversarial learning. In our experiments TIME achieves state45;of45;the45;art (SOTA) performance on the CUB and MS45;COCO dataset (Inception Score of 4.91 and Frechet Inception Distance of 14.3 on CUB) and shows promising performance on MS45;COCO on image captioning and downstream vision45;language tasks.
