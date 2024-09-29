---
layout: publication
title: SMDT&#58; Selective Memory-augmented Neural Document Translation
authors: Zhang Xu, Yang Jian, Huang Haoyang, Ma Shuming, Zhang Dongdong, Li Jinlong, Wei Furu
conference: "Arxiv"
year: 2022
bibkey: zhang2022selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.01631"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
Existing document-level neural machine translation (NMT) models have sufficiently explored different context settings to provide guidance for target generation. However little attention is paid to inaugurate more diverse context for abundant context information. In this paper we propose a Selective Memory-augmented Neural Document Translation model to deal with documents containing large hypothesis space of the context. Specifically we retrieve similar bilingual sentence pairs from the training corpus to augment global context and then extend the two-stream attention model with selective mechanism to capture local context and diverse global contexts. This unified approach allows our model to be trained elegantly on three publicly document-level machine translation datasets and significantly outperforms previous document-level NMT models.
