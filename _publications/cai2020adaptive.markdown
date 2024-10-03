---
layout: publication
title: 'Adaptive Parameterization For Neural Dialogue Generation'
authors: Cai Hengyi, Chen Hongshen, Zhang Cheng, Song Yonghao, Zhao Xiaofang, Yin Dawei
conference: "Arxiv"
year: 2020
bibkey: cai2020adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2001.06626"}
tags: ['Applications', 'Reinforcement Learning']
---
Neural conversation systems generate responses based on the sequence-to-sequence (SEQ2SEQ) paradigm. Typically, the model is equipped with a single set of learned parameters to generate responses for given input contexts. When confronting diverse conversations, its adaptability is rather limited and the model is hence prone to generate generic responses. In this work, we propose an \{\bf Ada\}ptive \{\bf N\}eural \{\bf D\}ialogue generation model, \textsc\{AdaND\}, which manages various conversations with conversation-specific parameterization. For each conversation, the model generates parameters of the encoder-decoder by referring to the input context. In particular, we propose two adaptive parameterization mechanisms: a context-aware and a topic-aware parameterization mechanism. The context-aware parameterization directly generates the parameters by capturing local semantics of the given context. The topic-aware parameterization enables parameter sharing among conversations with similar topics by first inferring the latent topics of the given context and then generating the parameters with respect to the distributional topics. Extensive experiments conducted on a large-scale real-world conversational dataset show that our model achieves superior performance in terms of both quantitative metrics and human evaluations.
