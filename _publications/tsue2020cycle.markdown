---
layout: publication
title: 'Cycle Text-to-image GAN With BERT'
authors: Trevor Tsue, Samir Sen, Jason Li
conference: "Arxiv"
year: 2020
bibkey: tsue2020cycle
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2003.12137"}
tags: ['BERT', 'Model Architecture', 'Attention Mechanism', 'Reinforcement Learning']
---
We explore novel approaches to the task of image generation from their
respective captions, building on state-of-the-art GAN architectures.
Particularly, we baseline our models with the Attention-based GANs that learn
attention mappings from words to image features. To better capture the features
of the descriptions, we then built a novel cyclic design that learns an inverse
function to maps the image back to original caption. Additionally, we
incorporated recently developed BERT pretrained word embeddings as our initial
text featurizer and observe a noticeable improvement in qualitative and
quantitative performance compared to the Attention GAN baseline.
