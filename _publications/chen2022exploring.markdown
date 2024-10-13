---
layout: publication
title: 'Exploring And Exploiting Multi-granularity Representations For Machine Reading Comprehension'
authors: Chen Nuo, You Chenyu
conference: "Arxiv"
year: 2022
bibkey: chen2022exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.08750"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recently, the attention-enhanced multi-layer encoder, such as Transformer,
has been extensively studied in Machine Reading Comprehension (MRC). To predict
the answer, it is common practice to employ a predictor to draw information
only from the final encoder layer which generates the coarse-grained
representations of the source sequences, i.e., passage and question. The
analysis shows that the representation of source sequence becomes more
coarse-grained from finegrained as the encoding layer increases. It is
generally believed that with the growing number of layers in deep neural
networks, the encoding process will gather relevant information for each
location increasingly, resulting in more coarse-grained representations, which
adds the likelihood of similarity to other locations (referring to
homogeneity). Such phenomenon will mislead the model to make wrong judgement
and degrade the performance. In this paper, we argue that it would be better if
the predictor could exploit representations of different granularity from the
encoder, providing different views of the source sequences, such that the
expressive power of the model could be fully utilized. To this end, we propose
a novel approach called Adaptive Bidirectional Attention-Capsule Network
(ABA-Net), which adaptively exploits the source representations of different
levels to the predictor. Furthermore, due to the better representations are at
the core for boosting MRC performance, the capsule network and self-attention
module are carefully designed as the building blocks of our encoders, which
provides the capability to explore the local and global representations,
respectively. Experimental results on three benchmark datasets, i.e., SQuAD
1.0, SQuAD 2.0 and COQA, demonstrate the effectiveness of our approach. In
particular, we set the new state-of-the-art performance on the SQuAD 1.0
dataset
