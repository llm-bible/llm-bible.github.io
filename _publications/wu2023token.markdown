---
layout: publication
title: TLM Token45;level Masking For Transformers
authors: Wu Yangjun, Fang Kebin, Zhang Dongxiang, Wang Han, Zhang Hao, Chen Gang
conference: "Arxiv"
year: 2023
bibkey: wu2023token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18738"}
  - {name: "Code", url: "https://github.com/Young1993/tlm"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Structured dropout approaches such as attention dropout and DropHead have been investigated to regularize the multi45;head attention mechanism in Transformers. In this paper we propose a new regularization scheme based on token45;level rather than structure45;level to reduce overfitting. Specifically we devise a novel Token45;Level Masking (TLM) training strategy for Transformers to regularize the connections of self45;attention which consists of two masking techniques that are effective and easy to implement. The underlying idea is to manipulate the connections between tokens in the multi45;head attention via masking where the networks are forced to exploit partial neighbors information to produce a meaningful representation. The generality and effectiveness of TLM are thoroughly evaluated via extensive experiments on 4 diversified NLP tasks across 18 datasets including natural language understanding benchmark GLUE ChineseGLUE Chinese Grammatical Error Correction and data45;to45;text generation. The results indicate that TLM can consistently outperform attention dropout and DropHead e.g. it increases by 0.5 points relative to DropHead with BERT45;large on GLUE. Moreover TLM can establish a new record on the data45;to45;text benchmark Rotowire (18.93 BLEU). Our code will be publicly available at https://github.com/Young1993/tlm.
