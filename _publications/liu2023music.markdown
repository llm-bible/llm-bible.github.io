---
layout: publication
title: 'Music Understanding Llama: Advancing Text-to-music Generation With Question Answering And Captioning'
authors: Shansong Liu, Atin Sakkeer Hussain, Chenshuo Sun, Ying Shan
conference: "Arxiv"
year: 2023
bibkey: liu2023music
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11276"}
tags: ['ACL', 'TACL', 'Training Techniques', 'Applications']
---
Text-to-music generation (T2M-Gen) faces a major obstacle due to the scarcity
of large-scale publicly available music datasets with natural language
captions. To address this, we propose the Music Understanding LLaMA (MU-LLaMA),
capable of answering music-related questions and generating captions for music
files. Our model utilizes audio representations from a pretrained MERT model to
extract music features. However, obtaining a suitable dataset for training the
MU-LLaMA model remains challenging, as existing publicly accessible audio
question answering datasets lack the necessary depth for open-ended music
question answering. To fill this gap, we present a methodology for generating
question-answer pairs from existing audio captioning datasets and introduce the
MusicQA Dataset designed for answering open-ended music-related questions. The
experiments demonstrate that the proposed MU-LLaMA model, trained on our
designed MusicQA dataset, achieves outstanding performance in both music
question answering and music caption generation across various metrics,
outperforming current state-of-the-art (SOTA) models in both fields and
offering a promising advancement in the T2M-Gen research field.
