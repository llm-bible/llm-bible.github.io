---
layout: publication
title: Sharing Attention Weights For Fast Transformer
authors: Xiao Tong, Li Yinqiao, Zhu Jingbo, Yu Zhengtao, Liu Tongran
conference: "Arxiv"
year: 2019
bibkey: xiao2019sharing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1906.11024"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Recently the Transformer machine translation system has shown strong results by stacking attention layers on both the source and target45;language sides. But the inference of this model is slow due to the heavy use of dot45;product attention in auto45;regressive decoding. In this paper we speed up Transformer via a fast and lightweight attention model. More specifically we share attention weights in adjacent layers and enable the efficient re45;use of hidden states in a vertical manner. Moreover the sharing policy can be jointly learned with the MT model. We test our approach on ten WMT and NIST OpenMT tasks. Experimental results show that it yields an average of 1.3X speed45;up (with almost no decrease in BLEU) on top of a state45;of45;the45;art implementation that has already adopted a cache for fast inference. Also our approach obtains a 1.8X speed45;up when it works with the textsc123;Aan125; model. This is even 16 times faster than the baseline with no use of the attention cache.
