---
layout: publication
title: 'Reproducing Whisper-style Training Using An Open-source Toolkit And Publicly Available Data'
authors: Peng Yifan, Tian Jinchuan, Yan Brian, Berrebbi Dan, Chang Xuankai, Li Xinjian, Shi Jiatong, Arora Siddhant, Chen William, Sharma Roshan, Zhang Wangyou, Sudo Yui, Shakeel Muhammad, Jung Jee-weon, Maiti Soumi, Watanabe Shinji
conference: "Arxiv"
year: 2023
bibkey: peng2023reproducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.13876"}
tags: ['Bias Mitigation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fairness', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Pre-training speech models on large volumes of data has achieved remarkable success. OpenAI Whisper is a multilingual multitask model trained on 680k hours of supervised speech data. It generalizes well to various speech recognition and translation benchmarks even in a zero-shot setup. However, the full pipeline for developing such models (from data collection to training) is not publicly accessible, which makes it difficult for researchers to further improve its performance and address training-related issues such as efficiency, robustness, fairness, and bias. This work presents an Open Whisper-style Speech Model (OWSM), which reproduces Whisper-style training using an open-source toolkit and publicly available data. OWSM even supports more translation directions and can be more efficient to train. We will publicly release all scripts used for data preparation, training, inference, and scoring as well as pre-trained models and training logs to promote open science.
