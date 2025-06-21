---
layout: publication
title: 'Smallcap: Lightweight Image Captioning Prompted With Retrieval Augmentation'
authors: Rita Ramos, Bruno Martins, Desmond Elliott, Yova Kementchedjhieva
conference: Arxiv
year: 2022
citations: 55
bibkey: ramos2022lightweight
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.15323'}]
tags: [GPT, Pre-Training, Prompting]
---
Recent advances in image captioning have focused on scaling the data and
model size, substantially increasing the cost of pre-training and finetuning.
As an alternative to large models, we present SmallCap, which generates a
caption conditioned on an input image and related captions retrieved from a
datastore. Our model is lightweight and fast to train, as the only learned
parameters are in newly introduced cross-attention layers between a pre-trained
CLIP encoder and GPT-2 decoder. SmallCap can transfer to new domains without
additional finetuning and can exploit large-scale data in a training-free
fashion since the contents of the datastore can be readily replaced. Our
experiments show that SmallCap, trained only on COCO, has competitive
performance on this benchmark, and also transfers to other domains without
retraining, solely through retrieval from target-domain data. Further
improvement is achieved through the training-free exploitation of diverse
human-labeled and web data, which proves to be effective for a range of
domains, including the nocaps benchmark, designed to test generalization to
unseen visual concepts.