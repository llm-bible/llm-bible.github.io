---
layout: publication
title: Lmcap Few-shot Multilingual Image Captioning By Retrieval Augmented Language Model Prompting
authors: Ramos Rita, Martins Bruno, Elliott Desmond
conference: "Arxiv"
year: 2023
bibkey: ramos2023lmcap
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19821"}
tags: ['Few Shot', 'Prompting', 'RAG', 'Training Techniques']
---
Multilingual image captioning has recently been tackled by training with large-scale machine translated data which is an expensive noisy and time-consuming process. Without requiring any multilingual caption data we propose LMCap an image-blind few-shot multilingual captioning model that works by prompting a language model with retrieved captions. Specifically instead of following the standard encoder-decoder paradigm given an image LMCap first retrieves the captions of similar images using a multilingual CLIP encoder. These captions are then combined into a prompt for an XGLM decoder in order to generate captions in the desired language. In other words the generation model does not directly process the image instead processing retrieved captions. Experiments on the XM3600 dataset of geographically diverse images show that our model is competitive with fully-supervised multilingual captioning models without requiring any supervised training on any captioning data.
