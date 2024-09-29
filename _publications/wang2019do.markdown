---
layout: publication
title: Do Multi-hop Readers Dream Of Reasoning Chains?
authors: Wang Haoyu, Yu Mo, Guo Xiaoxiao, Das Rajarshi, Xiong Wenhan, Gao Tian
conference: "Arxiv"
year: 2019
bibkey: wang2019do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.14520"}
tags: ['Applications', 'BERT', 'Model Architecture']
---
General Question Answering (QA) systems over texts require the multi-hop reasoning capability i.e. the ability to reason with information collected from multiple passages to derive the answer. In this paper we conduct a systematic analysis to assess such an ability of various existing models proposed for multi-hop QA tasks. Specifically our analysis investigates that whether providing the full reasoning chain of multiple passages instead of just one final passage where the answer appears could improve the performance of the existing QA models. Surprisingly when using the additional evidence passages the improvements of all the existing multi-hop reading approaches are rather limited with the highest error reduction of 5.837; on F1 (corresponding to 1.337; absolute improvement) from the BERT model. To better understand whether the reasoning chains could indeed help find correct answers we further develop a co-matching-based method that leads to 13.137; error reduction with passage chains when applied to two of our base readers (including BERT). Our results demonstrate the existence of the potential improvement using explicit multi-hop reasoning and the necessity to develop models with better reasoning abilities.
