---
layout: publication
title: Large-scale Representation Learning From Visually Grounded Untranscribed Speech
authors: Ilharco Gabriel, Zhang Yuan, Baldridge Jason
conference: "The SIGNLL Conference on Computational Natural Language Learning"
year: 2019
bibkey: ilharco2019large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.08782"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Systems that can associate images with their spoken audio captions are an important step towards visually grounded language learning. We describe a scalable method to automatically generate diverse audio for image captioning datasets. This supports pretraining deep networks for encoding both audio and images which we do via a dual encoder that learns to align latent representations from both modalities. We show that a masked margin softmax loss for such models is superior to the standard triplet loss. We fine-tune these models on the Flickr8k Audio Captions Corpus and obtain state-of-the-art results---improving recall in the top 10 from 29.637; to 49.537;. We also obtain human ratings on retrieval outputs to better assess the impact of incidentally matching image-caption pairs that were not associated in the data finding that automatic evaluation substantially underestimates the quality of the retrieved results.
