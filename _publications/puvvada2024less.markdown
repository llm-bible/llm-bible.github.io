---
layout: publication
title: 'Less Is More: Accurate Speech Recognition & Translation Without Web-scale Data'
authors: Krishna C. Puvvada, Piotr Żelasko, He Huang, Oleksii Hrinchuk, Nithin Rao Koluguri, Kunal Dhawan, Somshubra Majumdar, Elena Rastorgueva, Zhehuai Chen, Vitaly Lavrukhin, Jagadeesh Balam, Boris Ginsburg
conference: "Arxiv"
year: 2024
bibkey: puvvada2024less
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19674"}
tags: ['Fine-Tuning', 'INTERSPEECH', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Recent advances in speech recognition and translation rely on hundreds of
thousands of hours of Internet speech data. We argue that state-of-the art
accuracy can be reached without relying on web-scale data. Canary -
multilingual ASR and speech translation model, outperforms current
state-of-the-art models - Whisper, OWSM, and Seamless-M4T on English, French,
Spanish, and German languages, while being trained on an order of magnitude
less data than these models. Three key factors enables such data-efficient
model: (1) a FastConformer-based attention encoder-decoder architecture (2)
training on synthetic data generated with machine translation and (3) advanced
training techniques: data-balancing, dynamic data blending, dynamic bucketing
and noise-robust fine-tuning. The model, weights, and training code will be
open-sourced.
