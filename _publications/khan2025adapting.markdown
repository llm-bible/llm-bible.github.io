---
layout: publication
title: 'Chitranuvad: Adapting Multi-lingual Llms For Multimodal Translation'
authors: Shaharukh Khan, Ayush Tarun, Ali Faraz, Palash Kamble, Vivek Dahiya, Praveen Pokala, Ashish Kulkarni, Chandra Khatri, Abhinav Ravi, Shubham Agarwal
conference: "https://aclanthology.org/2024.wmt-1.80/"
year: 2025
bibkey: khan2025adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20420"}
tags: ['GPT', 'Multimodal Models', 'Pretraining Methods']
---
In this work, we provide the system description of our submission as part of
the English to Lowres Multimodal Translation Task at the Workshop on Asian
Translation (WAT2024). We introduce Chitranuvad, a multimodal model that
effectively integrates Multilingual LLM and a vision module for Multimodal
Translation. Our method uses a ViT image encoder to extract visual
representations as visual token embeddings which are projected to the LLM space
by an adapter layer and generates translation in an autoregressive fashion. We
participated in all the three tracks (Image Captioning, Text only and
Multimodal translation tasks) for Indic languages (ie. English translation to
Hindi, Bengali and Malyalam) and achieved SOTA results for Hindi in all of them
on the Challenge set while remaining competitive for the other languages in the
shared task.
