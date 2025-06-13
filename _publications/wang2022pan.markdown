---
layout: publication
title: 'Pan More Gold From The Sand: Refining Open-domain Dialogue Training With Noisy Self-retrieval Generation'
authors: Yihe Wang, Yitong Li, Yasheng Wang, Fei Mi, Pingyi Zhou, Xin Wang, Jin Liu, Xin Jiang, Qun Liu
conference: "Arxiv"
year: 2022
bibkey: wang2022pan
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2201.11367'}
tags: ['GPT', 'Model Architecture', 'BERT', 'Tools', 'Training Techniques', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Real human conversation data are complicated, heterogeneous, and noisy, from
which building open-domain dialogue systems remains a challenging task. In
fact, such dialogue data still contains a wealth of information and knowledge,
however, they are not fully explored. In this paper, we show existing
open-domain dialogue generation methods that memorize context-response paired
data with autoregressive or encode-decode language models underutilize the
training data. Different from current approaches, using external knowledge, we
explore a retrieval-generation training framework that can take advantage of
the heterogeneous and noisy training data by considering them as "evidence". In
particular, we use BERTScore for retrieval, which gives better qualities of the
evidence and generation. Experiments over publicly available datasets
demonstrate that our method can help models generate better responses, even
such training data are usually impressed as low-quality data. Such performance
gain is comparable with those improved by enlarging the training set, even
better. We also found that the model performance has a positive correlation
with the relevance of the retrieved evidence. Moreover, our method performed
well on zero-shot experiments, which indicates that our method can be more
robust to real-world data.
