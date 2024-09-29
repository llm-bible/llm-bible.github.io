---
layout: publication
title: Beyond English-Centric Bitexts for Better Multilingual Language Representation Learning
authors: Patra Barun, Singhal Saksham, Huang Shaohan, Chi Zewen, Dong Li, Wei Furu, Chaudhary Vishrav, Song Xia
conference: "Arxiv"
year: 2022
bibkey: patra2022beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.14867"}
tags: ['Applications', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
In this paper we elaborate upon recipes for building multilingual representation models that are not only competitive with existing state-of-the-art models but are also more parameter efficient thereby promoting better adoption in resource-constrained scenarios and practical applications. We show that going beyond English-centric bitexts coupled with a novel sampling strategy aimed at reducing under-utilization of training data substantially boosts performance across model sizes for both Electra and MLM pre-training objectives. We introduce XY-LENT X-Y bitext enhanced Language ENcodings using Transformers which not only achieves state-of-the-art performance over 5 cross-lingual tasks within all model size bands is also competitive across bands. Our XY-LENT XL variant outperforms XLM-RXXL and exhibits competitive performance with mT5 XXL while being 5x and 6x smaller respectively. We then show that our proposed method helps ameliorate the curse of multilinguality with the XY-LENT XL achieving 99.3 GLUE performance and 98.5 SQuAD 2.0 performance compared to a SoTA English only model in the same size band. We then analyze our models performance on extremely low resource languages and posit that scaling alone may not be sufficient for improving the performance in this scenario
