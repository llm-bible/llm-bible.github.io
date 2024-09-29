---
layout: publication
title: Diversifying Dialog Generation Via Adaptive Label Smoothing
authors: Wang Yida, Zheng Yinhe, Jiang Yong, Huang Minlie
conference: "Arxiv"
year: 2021
bibkey: wang2021diversifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.14556"}
tags: ['Applications', 'Training Techniques']
---
Neural dialogue generation models trained with the one45;hot target distribution suffer from the over45;confidence issue which leads to poor generation diversity as widely reported in the literature. Although existing approaches such as label smoothing can alleviate this issue they fail to adapt to diverse dialog contexts. In this paper we propose an Adaptive Label Smoothing (AdaLabel) approach that can adaptively estimate a target label distribution at each time step for different contexts. The maximum probability in the predicted distribution is used to modify the soft target distribution produced by a novel light45;weight bi45;directional decoder module. The resulting target distribution is aware of both previous and future contexts and is adjusted to avoid over45;training the dialogue model. Our model can be trained in an end45;to45;end manner. Extensive experiments on two benchmark datasets show that our approach outperforms various competitive baselines in producing diverse responses.
