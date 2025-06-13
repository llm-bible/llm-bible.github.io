---
layout: publication
title: 'Reproducing Whisper-style Training Using An Open-source Toolkit And Publicly Available Data'
authors: Yifan Peng, Jinchuan Tian, Brian Yan, Dan Berrebbi, Xuankai Chang, Xinjian Li, Jiatong Shi, Siddhant Arora, William Chen, Roshan Sharma, Wangyou Zhang, Yui Sudo, Muhammad Shakeel, Jee-weon Jung, Soumi Maiti, Shinji Watanabe
conference: "Arxiv"
year: 2023
bibkey: peng2023reproducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.13876'}
tags: ['Dataset', 'Ethics and Bias', 'INTERSPEECH', 'Security', 'Efficiency and Optimization', 'Training Techniques', 'Fairness', 'Bias Mitigation', 'Reinforcement Learning', 'Pre-Training']
---
Pre-training speech models on large volumes of data has achieved remarkable
success. OpenAI Whisper is a multilingual multitask model trained on 680k hours
of supervised speech data. It generalizes well to various speech recognition
and translation benchmarks even in a zero-shot setup. However, the full
pipeline for developing such models (from data collection to training) is not
publicly accessible, which makes it difficult for researchers to further
improve its performance and address training-related issues such as efficiency,
robustness, fairness, and bias. This work presents an Open Whisper-style Speech
Model (OWSM), which reproduces Whisper-style training using an open-source
toolkit and publicly available data. OWSM even supports more translation
directions and can be more efficient to train. We will publicly release all
scripts used for data preparation, training, inference, and scoring as well as
pre-trained models and training logs to promote open science.
