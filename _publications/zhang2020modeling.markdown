---
layout: publication
title: Modeling Topical Relevance For Multi45;turn Dialogue Generation
authors: Zhang Hainan, Lan Yanyan, Pang Liang, Chen Hongshen, Ding Zhuoye, Yin Dawei
conference: "the"
year: 2020
bibkey: zhang2020modeling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.12735"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
Topic drift is a common phenomenon in multi45;turn dialogue. Therefore an ideal dialogue generation models should be able to capture the topic information of each context detect the relevant context and produce appropriate responses accordingly. However existing models usually use word or sentence level similarities to detect the relevant contexts which fail to well capture the topical level relevance. In this paper we propose a new model named STAR45;BTM to tackle this problem. Firstly the Biterm Topic Model is pre45;trained on the whole training dataset. Then the topic level attention weights are computed based on the topic representation of each context. Finally the attention weights and the topic distribution are utilized in the decoding process to generate the corresponding responses. Experimental results on both Chinese customer services data and English Ubuntu dialogue data show that STAR45;BTM significantly outperforms several state45;of45;the45;art methods in terms of both metric45;based and human evaluations.
