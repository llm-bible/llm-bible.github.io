---
layout: publication
title: BERT45;JAM Boosting Bert45;enhanced Neural Machine Translation With Joint Attention
authors: Zhang Zhebin, Wu Sai, Jiang Dawei, Chen Gang
conference: "Arxiv"
year: 2020
bibkey: zhang2020bert
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.04266"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
BERT45;enhanced neural machine translation (NMT) aims at leveraging BERT45;encoded representations for translation tasks. A recently proposed approach uses attention mechanisms to fuse Transformers encoder and decoder layers with BERTs last45;layer representation and shows enhanced performance. However their method doesnt allow for the flexible distribution of attention between the BERT representation and the encoder/decoder representation. In this work we propose a novel BERT45;enhanced NMT model called BERT45;JAM which improves upon existing models from two aspects 1) BERT45;JAM uses joint45;attention modules to allow the encoder/decoder layers to dynamically allocate attention between different representations and 2) BERT45;JAM allows the encoder/decoder layers to make use of BERTs intermediate representations by composing them using a gated linear unit (GLU). We train BERT45;JAM with a novel three45;phase optimization strategy that progressively unfreezes different components of BERT45;JAM. Our experiments show that BERT45;JAM achieves SOTA BLEU scores on multiple translation tasks.
