---
layout: publication
title: Less Is More Accurate Speech Recognition amp; Translation Without Web-scale Data
authors: Puvvada Krishna C., Żelasko Piotr, Huang He, Hrinchuk Oleksii, Koluguri Nithin Rao, Dhawan Kunal, Majumdar Somshubra, Rastorgueva Elena, Chen Zhehuai, Lavrukhin Vitaly, Balam Jagadeesh, Ginsburg Boris
conference: "Arxiv"
year: 2024
bibkey: puvvada2024less
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19674"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Recent advances in speech recognition and translation rely on hundreds of thousands of hours of Internet speech data. We argue that state-of-the art accuracy can be reached without relying on web-scale data. Canary - multilingual ASR and speech translation model outperforms current state-of-the-art models - Whisper OWSM and Seamless-M4T on English French Spanish and German languages while being trained on an order of magnitude less data than these models. Three key factors enables such data-efficient model (1) a FastConformer-based attention encoder-decoder architecture (2) training on synthetic data generated with machine translation and (3) advanced training techniques data-balancing dynamic data blending dynamic bucketing and noise-robust fine-tuning. The model weights and training code will be open-sourced.
