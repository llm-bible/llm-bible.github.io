---
layout: publication
title: Extrapolating Large Language Models to Non-English by Aligning Languages
authors: Zhu Wenhao, Lv Yunzhe, Dong Qingxiu, Yuan Fei, Xu Jingjing, Huang Shujian, Kong Lingpeng, Chen Jiajun, Li Lei
conference: "Arxiv"
year: 2023
bibkey: zhu2023extrapolating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04948"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Large Scale Training', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques']
---
Existing large language models show disparate capability across different languages due to the imbalance in the training data. Their performances on English tasks are often stronger than on tasks of other languages. In this paper we empower pre-trained LLMs on non-English languages by building semantic alignment across languages. We start from targeting individual languages by performing cross-lingual instruction-tuning (CoIT) on LLaMA i.e. tuning it with translation task data and cross-lingual general task data to obtain cross-lingual models (x-LLaMAs) and formulate underlying scaling laws to investigate the advantages of using scalable translation data. Then we perform multilingual instruction-tuning (MuIT) with mixed resources to build multilingual m-LLaMA. We also illustrate how we leverage the scaling laws to optimize data allocation in a resource-constrained setting. Experiment results on cross-lingual benchmarks XQUAD and MLQA show that x-LLaMAs surpass the English instruction-tuned counterpart (Alpaca) by an average of 27.83 across six non-English languages. Evaluation results on translation dataset Flores-101 show that x-LLaMAs outperform previous LLaMA-based models by an average of 18.89. Encouragingly m-LLaMA achieves comparable performance to x-LLaMAs on individual languages and demonstrates the ability to follow multilingual instructions. Further analysis on response content and representation space reveals the alignment of the multilingual semantic space within the middle layers of m-LLaMA.
