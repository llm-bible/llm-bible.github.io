---
layout: publication
title: 'Layalign: Enhancing Multilingual Reasoning In Large Language Models Via Layer-wise Adaptive Fusion And Alignment Strategy'
authors: Zhiwen Ruan, Yixia Li, He Zhu, Longyue Wang, Weihua Luo, Kaifu Zhang, Yun Chen, Guanhua Chen
conference: "Arxiv"
year: 2025
bibkey: ruan2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11405"}
tags: ['RAG', 'Tools', 'Merging', 'Reinforcement Learning']
---
Despite being pretrained on multilingual corpora, large language models
(LLMs) exhibit suboptimal performance on low-resource languages. Recent
approaches have leveraged multilingual encoders alongside LLMs by introducing
trainable parameters connecting the two models. However, these methods
typically focus on the encoder's output, overlooking valuable information from
other layers. We propose \aname (\mname), a framework that integrates
representations from all encoder layers, coupled with the \attaname mechanism
to enable layer-wise interaction between the LLM and the multilingual encoder.
Extensive experiments on multilingual reasoning tasks, along with analyses of
learned representations, show that our approach consistently outperforms
existing baselines.
