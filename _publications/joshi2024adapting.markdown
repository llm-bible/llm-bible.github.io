---
layout: publication
title: 'Adapting Multilingual Llms To Low-resource Languages Using Continued Pre-training And Synthetic Corpus'
authors: Raviraj Joshi, Kanishk Singla, Anusha Kamath, Raunak Kalani, Rakesh Paul, Utkarsh Vaidya, Sanjay Singh Chauhan, Niranjan Wartikar, Eileen Long
conference: "Arxiv"
year: 2024
bibkey: joshi2024adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14815"}
tags: ['Training Techniques', 'Pre-Training', 'Reinforcement Learning']
---
Multilingual LLMs support a variety of languages; however, their performance
is suboptimal for low-resource languages. In this work, we emphasize the
importance of continued pre-training of multilingual LLMs and the use of
translation-based synthetic pre-training corpora for improving LLMs in
low-resource languages. We conduct our study in the context of the low-resource
Indic language Hindi. We introduce Nemotron-Mini-Hindi 4B, a bilingual SLM
supporting both Hindi and English, based on Nemotron-Mini 4B. The model is
trained using a mix of real and synthetic Hindi + English tokens, with
continuous pre-training performed on 400B tokens. We demonstrate that both the
base and instruct models achieve state-of-the-art results on Hindi benchmarks
while remaining competitive on English tasks. Additionally, we observe that the
continued pre-training approach enhances the model's overall factual accuracy.
We perform an ablation study to highlight the impact of Hindi pre-training,
showing significant improvements in Hindi chat capabilities and factual
accuracy, which cannot be achieved through Hindi alignment alone.
