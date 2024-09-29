---
layout: publication
title: Instantbooth Personalized Text45;to45;image Generation Without Test45;time Finetuning
authors: Shi Jing, Xiong Wei, Lin Zhe, Jung Hyun Joon
conference: "Arxiv"
year: 2023
bibkey: shi2023personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.03411"}
tags: ['Pretraining Methods']
---
Recent advances in personalized image generation allow a pre45;trained text45;to45;image model to learn a new concept from a set of images. However existing personalization approaches usually require heavy test45;time finetuning for each concept which is time45;consuming and difficult to scale. We propose InstantBooth a novel approach built upon pre45;trained text45;to45;image models that enables instant text45;guided image personalization without any test45;time finetuning. We achieve this with several major components. First we learn the general concept of the input images by converting them to a textual token with a learnable image encoder. Second to keep the fine details of the identity we learn rich visual feature representation by introducing a few adapter layers to the pre45;trained model. We train our components only on text45;image pairs without using paired images of the same concept. Compared to test45;time finetuning45;based methods like DreamBooth and Textual45;Inversion our model can generate competitive results on unseen concepts concerning language45;image alignment image fidelity and identity preservation while being 100 times faster.
