---
layout: publication
title: Extrapolating Large Language Models To Non45;english By Aligning Languages
authors: Zhu Wenhao, Lv Yunzhe, Dong Qingxiu, Yuan Fei, Xu Jingjing, Huang Shujian, Kong Lingpeng, Chen Jiajun, Li Lei
conference: "Arxiv"
year: 2023
bibkey: zhu2023extrapolating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04948"}
tags: ['Efficiency And Optimization', 'Large Scale Training', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques']
---
Existing large language models show disparate capability across different languages due to the imbalance in the training data. Their performances on English tasks are often stronger than on tasks of other languages. In this paper we empower pre45;trained LLMs on non45;English languages by building semantic alignment across languages. We start from targeting individual languages by performing cross45;lingual instruction45;tuning (CoIT) on LLaMA i.e. tuning it with translation task data and cross45;lingual general task data to obtain cross45;lingual models (x45;LLaMAs) and formulate underlying scaling laws to investigate the advantages of using scalable translation data. Then we perform multilingual instruction45;tuning (MuIT) with mixed resources to build multilingual m45;LLaMA. We also illustrate how we leverage the scaling laws to optimize data allocation in a resource45;constrained setting. Experiment results on cross45;lingual benchmarks XQUAD and MLQA show that x45;LLaMAs surpass the English instruction45;tuned counterpart (Alpaca) by an average of 27.8337; across six non45;English languages. Evaluation results on translation dataset Flores45;101 show that x45;LLaMAs outperform previous LLaMA45;based models by an average of 18.8937;. Encouragingly m45;LLaMA achieves comparable performance to x45;LLaMAs on individual languages and demonstrates the ability to follow multilingual instructions. Further analysis on response content and representation space reveals the alignment of the multilingual semantic space within the middle layers of m45;LLaMA.
