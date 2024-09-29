---
layout: publication
title: Glancing Future For Simultaneous Machine Translation
authors: Guo Shoutao, Zhang Shaolei, Feng Yang
conference: "Arxiv"
year: 2023
bibkey: guo2023glancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06179"}
tags: ['Applications', 'Training Techniques']
---
Simultaneous machine translation (SiMT) outputs translation while reading the source sentence. Unlike conventional sequence-to-sequence (seq2seq) training existing SiMT methods adopt the prefix-to-prefix (prefix2prefix) training where the model predicts target tokens based on partial source tokens. However the prefix2prefix training diminishes the ability of the model to capture global information and introduces forced predictions due to the absence of essential source information. Consequently it is crucial to bridge the gap between the prefix2prefix training and seq2seq training to enhance the translation capability of the SiMT model. In this paper we propose a novel method that glances future in curriculum learning to achieve the transition from the seq2seq training to prefix2prefix training. Specifically we gradually reduce the available source information from the whole sentence to the prefix corresponding to that latency. Our method is applicable to a wide range of SiMT methods and experiments demonstrate that our method outperforms strong baselines.
