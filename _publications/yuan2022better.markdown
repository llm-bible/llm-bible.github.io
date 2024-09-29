---
layout: publication
title: Hype Better Pre45;trained Language Model Fine45;tuning With Hidden Representation Perturbation
authors: Yuan Hongyi, Yuan Zheng, Tan Chuanqi, Huang Fei, Huang Songfang
conference: "Arxiv"
year: 2022
bibkey: yuan2022better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.08853"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer']
---
Language models with the Transformers structure have shown great performance in natural language processing. However there still poses problems when fine45;tuning pre45;trained language models on downstream tasks such as over45;fitting or representation collapse. In this work we propose HyPe a simple yet effective fine45;tuning technique to alleviate such problems by perturbing hidden representations of Transformers layers. Unlike previous works that only add noise to inputs or parameters we argue that the hidden representations of Transformers layers convey more diverse and meaningful language information. Therefore making the Transformers layers more robust to hidden representation perturbations can further benefit the fine45;tuning of PLMs en bloc. We conduct extensive experiments and analyses on GLUE and other natural language inference datasets. Results demonstrate that HyPe outperforms vanilla fine45;tuning and enhances generalization of hidden representations from different layers. In addition HyPe acquires negligible computational overheads and is better than and compatible with previous state45;of45;the45;art fine45;tuning techniques.
