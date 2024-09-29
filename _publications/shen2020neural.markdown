---
layout: publication
title: Neural Data-to-Text Generation via Jointly Learning the Segmentation and Correspondence
authors: Shen Xiaoyu, Chang Ernie, Su Hui, Zhou Jie, Klakow Dietrich
conference: "Arxiv"
year: 2020
bibkey: shen2020neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.01096"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'RAG']
---
The neural attention model has achieved great success in data-to-text generation tasks. Though usually excelling at producing fluent text it suffers from the problem of information missing repetition and hallucination. Due to the black-box nature of the neural attention architecture avoiding these problems in a systematic way is non-trivial. To address this concern we propose to explicitly segment target text into fragment units and align them with their data correspondences. The segmentation and correspondence are jointly learned as latent variables without any human annotations. We further impose a soft statistical constraint to regularize the segmental granularity. The resulting architecture maintains the same expressive power as neural attention models while being able to generate fully interpretable outputs with several times less computational cost. On both E2E and WebNLG benchmarks we show the proposed model consistently outperforms its neural attention counterparts.
