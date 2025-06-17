---
layout: publication
title: Neural Machine Translation With Phrase-level Universal Visual Representations
authors: Qingkai Fang, Yang Feng
conference: Arxiv
year: 2022
citations: 16
bibkey: fang2022neural
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.10299'}]
tags: [Multimodal Models]
---
Multimodal machine translation (MMT) aims to improve neural machine
translation (NMT) with additional visual information, but most existing MMT
methods require paired input of source sentence and image, which makes them
suffer from shortage of sentence-image pairs. In this paper, we propose a
phrase-level retrieval-based method for MMT to get visual information for the
source input from existing sentence-image data sets so that MMT can break the
limitation of paired sentence-image input. Our method performs retrieval at the
phrase level and hence learns visual information from pairs of source phrase
and grounded region, which can mitigate data sparsity. Furthermore, our method
employs the conditional variational auto-encoder to learn visual
representations which can filter redundant visual information and only retain
visual information related to the phrase. Experiments show that the proposed
method significantly outperforms strong baselines on multiple MMT datasets,
especially when the textual context is limited.