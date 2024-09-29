---
layout: publication
title: "Revisiting Token Dropping Strategy In Efficient BERT Pretraining"
authors: Zhong Qihuang, Ding Liang, Liu Juhua, Liu Xuebo, Zhang Min, Du Bo, Tao Dacheng
conference: "Arxiv"
year: 2023
bibkey: zhong2023revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15273"}
tags: ['BERT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Token dropping is a recently-proposed strategy to speed up the pretraining of masked language models such as BERT by skipping the computation of a subset of the input tokens at several middle layers. It can effectively reduce the training time without degrading much performance on downstream tasks. However we empirically find that token dropping is prone to a semantic loss problem and falls short in handling semantic-intense tasks. Motivated by this we propose a simple yet effective semantic-consistent learning method (ScTD) to improve the token dropping. ScTD aims to encourage the model to learn how to preserve the semantic information in the representation space. Extensive experiments on 12 tasks show that with the help of our ScTD token dropping can achieve consistent and significant performance gains across all task types and model sizes. More encouragingly ScTD saves up to 5737; of pretraining time and brings up to +1.5637; average improvement over the vanilla token dropping.
