---
layout: publication
title: Winner Team Mia At Textvqa Challenge 2021 Vision45;and45;language Representation Learning With Pre45;trained Sequence45;to45;sequence Model
authors: Qiao Yixuan, Chen Hao, Wang Jun, Chen Yihao, Ye Xianbin, Li Ziliang, Qi Xianbiao, Gao Peng, Xie Guotong
conference: "Arxiv"
year: 2021
bibkey: qiao2021winner
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.15332"}
tags: ['BERT', 'Language Modeling', 'Masked Language Model', 'Merging', 'Pretraining Methods', 'Training Techniques']
---
TextVQA requires models to read and reason about text in images to answer questions about them. Specifically models need to incorporate a new modality of text present in the images and reason over it to answer TextVQA questions. In this challenge we use generative model T5 for TextVQA task. Based on pre45;trained checkpoint T545;3B from HuggingFace repository two other pre45;training tasks including masked language modeling(MLM) and relative position prediction(RPP) are designed to better align object feature and scene text. In the stage of pre45;training encoder is dedicate to handle the fusion among multiple modalities question text object text labels scene text labels object visual features scene visual features. After that decoder generates the text sequence step45;by45;step cross entropy loss is required by default. We use a large45;scale scene text dataset in pre45;training and then fine45;tune the T545;3B with the TextVQA dataset only.
