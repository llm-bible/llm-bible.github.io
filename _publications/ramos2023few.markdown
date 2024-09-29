---
layout: publication
title: Lmcap Few45;shot Multilingual Image Captioning By Retrieval Augmented Language Model Prompting
authors: Ramos Rita, Martins Bruno, Elliott Desmond
conference: "Arxiv"
year: 2023
bibkey: ramos2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19821"}
tags: ['Prompting', 'RAG', 'Training Techniques']
---
Multilingual image captioning has recently been tackled by training with large45;scale machine translated data which is an expensive noisy and time45;consuming process. Without requiring any multilingual caption data we propose LMCap an image45;blind few45;shot multilingual captioning model that works by prompting a language model with retrieved captions. Specifically instead of following the standard encoder45;decoder paradigm given an image LMCap first retrieves the captions of similar images using a multilingual CLIP encoder. These captions are then combined into a prompt for an XGLM decoder in order to generate captions in the desired language. In other words the generation model does not directly process the image instead processing retrieved captions. Experiments on the XM3600 dataset of geographically diverse images show that our model is competitive with fully45;supervised multilingual captioning models without requiring any supervised training on any captioning data.
