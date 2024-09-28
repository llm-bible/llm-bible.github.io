---
layout: publication
title: Understanding the RoPE Extensions of Long-Context LLMs An Attention Perspective
authors: Zhong Meizhi, Zhang Chen, Lei Yikun, Liu Xikai, Gao Yan, Hu Yao, Chen Kehai, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: zhong2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13282"}
tags: ['ARXIV', 'Attention Mechanism', 'LLM', 'Model Architecture']
---
Enabling LLMs to handle lengthy context is currently a research hotspot. Most LLMs are built upon rotary position embedding (RoPE) a popular position encoding method. Therefore a prominent path is to extrapolate the RoPE trained on comparably short texts to far longer texts. A heavy bunch of efforts have been dedicated to boosting the extrapolation via extending the formulations of the RoPE however few of them have attempted to showcase their inner workings comprehensively. In this paper we are driven to offer a straightforward yet in-depth understanding of RoPE extensions from an attention perspective and on two benchmarking tasks. A broad array of experiments reveals several valuable findings 1) Maintaining attention patterns to those at the pretrained length improves extrapolation; 2) Large attention uncertainty leads to retrieval errors; 3) Using longer continual pretraining lengths for RoPE extensions could reduce attention uncertainty and significantly enhance extrapolation.
