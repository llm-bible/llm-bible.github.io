---
layout: publication
title: Visualizing And Understanding The Effectiveness Of BERT
authors: Hao Yaru, Dong Li, Wei Furu, Xu Ke
conference: "Arxiv"
year: 2019
bibkey: hao2019visualizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1908.05620"}
tags: ['BERT', 'Efficiency And Optimization', 'Model Architecture', 'Training Techniques']
---
Language model pre45;training such as BERT has achieved remarkable results in many NLP tasks. However it is unclear why the pre45;training45;then45;fine45;tuning paradigm can improve performance and generalization capability across different tasks. In this paper we propose to visualize loss landscapes and optimization trajectories of fine45;tuning BERT on specific datasets. First we find that pre45;training reaches a good initial point across downstream tasks which leads to wider optima and easier optimization compared with training from scratch. We also demonstrate that the fine45;tuning procedure is robust to overfitting even though BERT is highly over45;parameterized for downstream tasks. Second the visualization results indicate that fine45;tuning BERT tends to generalize better because of the flat and wide optima and the consistency between the training loss surface and the generalization error surface. Third the lower layers of BERT are more invariant during fine45;tuning which suggests that the layers that are close to input learn more transferable representations of language.
