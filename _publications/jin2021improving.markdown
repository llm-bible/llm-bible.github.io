---
layout: publication
title: 'Numgpt: Improving Numeracy Ability Of Generative Pre-trained Models'
authors: Zhihua Jin, Xin Jiang, Xingbo Wang, Qun Liu, Yong Wang, Xiaozhe Ren, Huamin Qu
conference: "Arxiv"
year: 2021
bibkey: jin2021improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2109.03137'}
tags: ['RAG', 'Training Techniques', 'Model Architecture', 'GPT', 'Pre-Training']
---
Existing generative pre-trained language models (e.g., GPT) focus on modeling
the language structure and semantics of general texts. However, those models do
not consider the numerical properties of numbers and cannot perform robustly on
numerical reasoning tasks (e.g., math word problems and measurement
estimation). In this paper, we propose NumGPT, a generative pre-trained model
that explicitly models the numerical properties of numbers in texts.
Specifically, it leverages a prototype-based numeral embedding to encode the
mantissa of the number and an individual embedding to encode the exponent of
the number. A numeral-aware loss function is designed to integrate numerals
into the pre-training objective of NumGPT. We conduct extensive experiments on
four different datasets to evaluate the numeracy ability of NumGPT. The
experiment results show that NumGPT outperforms baseline models (e.g., GPT and
GPT with DICE) on a range of numerical reasoning tasks such as measurement
estimation, number comparison, math word problems, and magnitude
classification. Ablation studies are also conducted to evaluate the impact of
pre-training and model hyperparameters on the performance.
