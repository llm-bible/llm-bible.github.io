---
layout: publication
title: RAT Retrieval-Augmented Transformer for Click-Through Rate Prediction
authors: Li Yushen, Wang Jinpeng, Dai Tao, Zhu Jieming, Yuan Jun, Zhang Rui, Xia Shu-tao
conference: "Arxiv"
year: 2024
bibkey: li2024rat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02249"}
  - {name: "Code", url: "https://github.com/YushenLi807/WWW24-RAT}"}
tags: ['Transformer', 'Applications', 'Has Code', 'Arxiv']
---
Predicting click-through rates (CTR) is a fundamental task for Web applications where a key issue is to devise effective models for feature interactions. Current methodologies predominantly concentrate on modeling feature interactions within an individual sample while overlooking the potential cross-sample relationships that can serve as a reference context to enhance the prediction. To make up for such deficiency this paper develops a Retrieval-Augmented Transformer (RAT) aiming to acquire fine-grained feature interactions within and across samples. By retrieving similar samples we construct augmented input for each target sample. We then build Transformer layers with cascaded attention to capture both intra- and cross-sample feature interactions facilitating comprehensive reasoning for improved CTR prediction while retaining efficiency. Extensive experiments on real-world datasets substantiate the effectiveness of RAT and suggest its advantage in long-tail scenarios. The code has been open-sourced at urlhttps://github.com/YushenLi807/WWW24-RAT}.
