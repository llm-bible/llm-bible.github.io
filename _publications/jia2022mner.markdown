---
layout: publication
title: 'MNER-QG: An End-to-end MRC Framework For Multimodal Named Entity Recognition
  With Query Grounding'
authors: Meihuizi Jia et al.
conference: Arxiv
year: 2022
citations: 27
bibkey: jia2022mner
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.14739'}]
tags: [Multimodal Models, Fine-Tuning, Attention Mechanism]
---
Multimodal named entity recognition (MNER) is a critical step in information
extraction, which aims to detect entity spans and classify them to
corresponding entity types given a sentence-image pair. Existing methods either
(1) obtain named entities with coarse-grained visual clues from attention
mechanisms, or (2) first detect fine-grained visual regions with toolkits and
then recognize named entities. However, they suffer from improper alignment
between entity types and visual regions or error propagation in the two-stage
manner, which finally imports irrelevant visual information into texts. In this
paper, we propose a novel end-to-end framework named MNER-QG that can
simultaneously perform MRC-based multimodal named entity recognition and query
grounding. Specifically, with the assistance of queries, MNER-QG can provide
prior knowledge of entity types and visual regions, and further enhance
representations of both texts and images. To conduct the query grounding task,
we provide manual annotations and weak supervisions that are obtained via
training a highly flexible visual grounding model with transfer learning. We
conduct extensive experiments on two public MNER datasets, Twitter2015 and
Twitter2017. Experimental results show that MNER-QG outperforms the current
state-of-the-art models on the MNER task, and also improves the query grounding
performance.