---
layout: publication
title: 'Investigating And Enhancing Vision-audio Capability In Omnimodal Large Language Models'
authors: Rui Hu, Delai Qiu, Shuyu Wei, Jiaming Zhang, Yining Wang, Shengping Liu, Jitao Sang
conference: "Arxiv"
year: 2025
bibkey: hu2025investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00059"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models', 'Distillation']
---
Omnimodal Large Language Models (OLLMs) have shown significant progress in integrating vision and text, but still struggle with integrating vision and audio, often exhibiting suboptimal performance when processing audio queries compared to text queries. This disparity is primarily due to insufficient alignment between vision and audio modalities during training, leading to inadequate attention to visual information when using audio queries. To mitigate this issue, we propose a Self-Knowledge Distillation (Self-KD) training method where the vision-text component of the OLLM serves as the teacher and the vision-audio component as the student. This enables the model to process audio in a manner analogous to its text processing. Our experimental results demonstrate that Self-KD is an effective method for enhancing the vision-audio capabilities of OLLMs by learning from the vision-text components, which subsequently improves the interaction between audio and images and results in improved performance on multimodal tasks.
