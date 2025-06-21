---
layout: publication
title: 'Rocketqav2: A Joint Training Method For Dense Passage Retrieval And Passage
  Re-ranking'
authors: Ruiyang Ren et al.
conference: Arxiv
year: 2021
citations: 69
bibkey: ren2021joint
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.07367'}, {name: Code,
    url: 'https://github.com/PaddlePaddle/RocketQA'}]
tags: [Efficiency and Optimization, Distillation]
---
In various natural language processing tasks, passage retrieval and passage
re-ranking are two key procedures in finding and ranking relevant information.
Since both the two procedures contribute to the final performance, it is
important to jointly optimize them in order to achieve mutual improvement. In
this paper, we propose a novel joint training approach for dense passage
retrieval and passage re-ranking. A major contribution is that we introduce the
dynamic listwise distillation, where we design a unified listwise training
approach for both the retriever and the re-ranker. During the dynamic
distillation, the retriever and the re-ranker can be adaptively improved
according to each other's relevance information. We also propose a hybrid data
augmentation strategy to construct diverse training instances for listwise
training approach. Extensive experiments show the effectiveness of our approach
on both MSMARCO and Natural Questions datasets. Our code is available at
https://github.com/PaddlePaddle/RocketQA.