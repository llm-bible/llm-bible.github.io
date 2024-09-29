---
layout: publication
title: Adalora Adaptive Budget Allocation For Parameter45;efficient Fine45;tuning
authors: Qingru Zhang, Minshuo Chen, Alexander Bukharin, Nikos Karampatziakis, Pengcheng He, Yu Cheng, Weizhu Chen, Tuo Zhao
conference: "Arxiv"
year: 2023
bibkey: zhang2023adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2303.10512v2"}
  - {name: "Code", url: "https://github.com/QingruZhang/AdaLoRA"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Reinforcement Learning']
---
Fine45;tuning large pre45;trained language models on downstream tasks has become an important paradigm in NLP. However common practice fine45;tunes all of the parameters in a pre45;trained model which becomes prohibitive when a large number of downstream tasks are present. Therefore many fine45;tuning methods are proposed to learn incremental updates of pre45;trained weights in a parameter efficient way e.g. low45;rank increments. These methods often evenly distribute the budget of incremental updates across all pre45;trained weight matrices and overlook the varying importance of different weight parameters. As a consequence the fine45;tuning performance is suboptimal. To bridge this gap we propose AdaLoRA which adaptively allocates the parameter budget among weight matrices according to their importance score. In particular AdaLoRA parameterizes the incremental updates in the form of singular value decomposition. Such a novel approach allows us to effectively prune the singular values of unimportant updates which is essentially to reduce their parameter budget but circumvent intensive exact SVD computations. We conduct extensive experiments with several pre45;trained models on natural language processing question answering and natural language generation to validate the effectiveness of AdaLoRA. Results demonstrate that AdaLoRA manifests notable improvement over baselines especially in the low budget settings. Our code is publicly available at https://github.com/QingruZhang/AdaLoRA .
