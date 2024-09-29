---
layout: publication
title: 'A Modular Task-oriented Dialogue System Using A Neural Mixture-of-experts'
authors: Pei Jiahuan, Ren Pengjie, De Rijke Maarten
conference: "Arxiv"
year: 2019
bibkey: pei2019modular
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1907.05346"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Tools']
---
End-to-end Task-oriented Dialogue Systems (TDSs) have attracted a lot of attention for their superiority (e.g. in terms of global optimization) over pipeline modularized TDSs. Previous studies on end-to-end TDSs use a single-module model to generate responses for complex dialogue contexts. However no model consistently outperforms the others in all cases. We propose a neural Modular Task-oriented Dialogue System(MTDS) framework in which a few expert bots are combined to generate the response for a given dialogue context. MTDS consists of a chair bot and several expert bots. Each expert bot is specialized for a particular situation e.g. one domain one type of action of a system etc. The chair bot coordinates multiple expert bots and adaptively selects an expert bot to generate the appropriate response. We further propose a Token-level Mixture-of-Expert (TokenMoE) model to implement MTDS where the expert bots predict multiple tokens at each timestamp and the chair bot determines the final generated token by fully taking into consideration the outputs of all expert bots. Both the chair bot and the expert bots are jointly trained in an end-to-end fashion. To verify the effectiveness of TokenMoE we carry out extensive experiments on a benchmark dataset. Compared with the baseline using a single-module model our TokenMoE improves the performance by 8.137; of inform rate and 0.837; of success rate.
