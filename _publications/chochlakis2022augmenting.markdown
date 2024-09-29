---
layout: publication
title: Vault Augmenting The Vision-and-language Transformer For Sentiment Classification On Social Media
authors: Chochlakis Georgios University Of Southern California, Srinivasan Tejas University Of Southern California, Thomason Jesse University Of Southern California, Narayanan Shrikanth University Of Southern California
conference: "Arxiv"
year: 2022
bibkey: chochlakis2022augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.09021"}
  - {name: "Code", url: "https://github.com/gchochla/VAuLT"}
tags: ['BERT', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
We propose the Vision-and-Augmented-Language Transformer (VAuLT). VAuLT is an extension of the popular Vision-and-Language Transformer (ViLT) and improves performance on vision-and-language (VL) tasks that involve more complex text inputs than image captions while having minimal impact on training and inference efficiency. ViLT importantly enables efficient training and inference in VL tasks achieved by encoding images using a linear projection of patches instead of an object detector. However it is pretrained on captioning datasets where the language input is simple literal and descriptive therefore lacking linguistic diversity. So when working with multimedia data in the wild such as multimodal social media data there is a notable shift from captioning language data as well as diversity of tasks. We indeed find evidence that the language capacity of ViLT is lacking. The key insight and novelty of VAuLT is to propagate the output representations of a large language model (LM) like BERT to the language input of ViLT. We show that joint training of the LM and ViLT can yield relative improvements up to 2037; over ViLT and achieve state-of-the-art or comparable performance on VL tasks involving richer language inputs and affective constructs such as for Target-Oriented Sentiment Classification in TWITTER-2015 and TWITTER-2017 and Sentiment Classification in MVSA-Single and MVSA-Multiple. Our code is available at https://github.com/gchochla/VAuLT.
