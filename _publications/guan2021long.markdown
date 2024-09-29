---
layout: publication
title: Long Text Generation By Modeling Sentence45;level And Discourse45;level Coherence
authors: Guan Jian, Mao Xiaoxi, Fan Changjie, Liu Zitao, Ding Wenbiao, Huang Minlie
conference: "Arxiv"
year: 2021
bibkey: guan2021long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.08963"}
tags: ['Applications', 'Language Modeling', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Generating long and coherent text is an important but challenging task particularly for open45;ended language generation tasks such as story generation. Despite the success in modeling intra45;sentence coherence existing generation models (e.g. BART) still struggle to maintain a coherent event sequence throughout the generated text. We conjecture that this is because of the difficulty for the decoder to capture the high45;level semantics and discourse structures in the context beyond token45;level co45;occurrence. In this paper we propose a long text generation model which can represent the prefix sentences at sentence level and discourse level in the decoding process. To this end we propose two pretraining objectives to learn the representations by predicting inter45;sentence semantic similarity and distinguishing between normal and shuffled sentence orders. Extensive experiments show that our model can generate more coherent texts than state45;of45;the45;art baselines.
