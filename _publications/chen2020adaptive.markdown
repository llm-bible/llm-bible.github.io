---
layout: publication
title: "Adaptive Bi-directional Attention: Exploring Multi-granularity Representations For Machine Reading Comprehension"
authors: Chen Nuo, Liu Fenglin, You Chenyu, Zhou Peilin, Zou Yuexian
conference: "Arxiv"
year: 2020
bibkey: chen2020adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.10877"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recently the attention-enhanced multi-layer encoder such as Transformer has been extensively studied in Machine Reading Comprehension (MRC). To predict the answer it is common practice to employ a predictor to draw information only from the final encoder layer which generates the (textit)coarse-grained representations of the source sequences i.e. passage and question. Previous studies have shown that the representation of source sequence becomes more (textit)coarse-grained from (textit)fine-grained as the encoding layer increases. It is generally believed that with the growing number of layers in deep neural networks the encoding process will gather relevant information for each location increasingly resulting in more (textit)coarse-grained representations which adds the likelihood of similarity to other locations (referring to homogeneity). Such a phenomenon will mislead the model to make wrong judgments so as to degrade the performance. To this end we propose a novel approach called Adaptive Bidirectional Attention which adaptively exploits the source representations of different levels to the predictor. Experimental results on the benchmark dataset SQuAD 2.0 demonstrate the effectiveness of our approach and the results are better than the previous state-of-the-art model by 2.537; EM and 2.337; F1 scores.
