---
layout: publication
title: Generative Calibration For In45;context Learning
authors: Jiang Zhongtao, Zhang Yuanzhe, Liu Cao, Zhao Jun, Liu Kang
conference: "Arxiv"
year: 2023
bibkey: jiang2023generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10266"}
tags: ['Prompting', 'Reinforcement Learning', 'Training Techniques']
---
As one of the most exciting features of large language models (LLMs) in45;context learning is a mixed blessing. While it allows users to fast45;prototype a task solver with only a few training examples the performance is generally sensitive to various configurations of the prompt such as the choice or order of the training examples. In this paper we for the first time theoretically and empirically identify that such a paradox is mainly due to the label shift of the in45;context model to the data distribution in which LLMs shift the label marginal p(y) while having a good label conditional p(xy). With this understanding we can simply calibrate the in45;context predictive distribution by adjusting the label marginal which is estimated via Monte45;Carlo sampling over the in45;context model i.e. generation of LLMs. We call our approach as generative calibration. We conduct exhaustive experiments with 12 text classification tasks and 12 LLMs scaling from 774M to 33B generally find that the proposed method greatly and consistently outperforms the ICL as well as state45;of45;the45;art calibration methods by up to 2737; absolute in macro45;F1. Meanwhile the proposed method is also stable under different prompt configurations.
