---
layout: publication
title: 'Building An Efficient And Effective Retrieval-based Dialogue System Via Mutual Learning'
authors: Chongyang Tao, Jiazhan Feng, Chang Liu, Juntao Li, Xiubo Geng, Daxin Jiang
conference: "Arxiv"
year: 2021
bibkey: tao2021building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.00159"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'BERT', 'Applications', 'Attention Mechanism']
---
Establishing retrieval-based dialogue systems that can select appropriate
responses from the pre-built index has gained increasing attention from
researchers. For this task, the adoption of pre-trained language models (such
as BERT) has led to remarkable progress in a number of benchmarks. There exist
two common approaches, including cross-encoders which perform full attention
over the inputs, and bi-encoders that encode the context and response
separately. The former gives considerable improvements in accuracy but is often
inapplicable in practice for large-scale retrieval given the cost of the full
attention required for each sample at test time. The latter is efficient for
billions of indexes but suffers from sub-optimal performance. In this work, we
propose to combine the best of both worlds to build a retrieval system.
Specifically, we employ a fast bi-encoder to replace the traditional
feature-based pre-retrieval model (such as BM25) and set the response
re-ranking model as a more complicated architecture (such as cross-encoder). To
further improve the effectiveness of our framework, we train the pre-retrieval
model and the re-ranking model at the same time via mutual learning, which
enables two models to learn from each other throughout the training process. We
conduct experiments on two benchmarks and evaluation results demonstrate the
efficiency and effectiveness of our proposed framework.
