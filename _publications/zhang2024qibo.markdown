---
layout: publication
title: Qibo A Large Language Model For Traditional Chinese Medicine
authors: Zhang Heyi, Wang Xin, Meng Zhaopeng, Chen Zhe, Zhuang Pengwei, Jia Yongzhe, Xu Dawei, Guo Wenbin
conference: "Arxiv"
year: 2024
bibkey: zhang2024qibo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16056"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) has made significant progress in a number of professional fields including medicine law and finance. However in traditional Chinese medicine (TCM) there are challenges such as the essential differences between theory and modern medicine the lack of specialized corpus resources and the fact that relying only on supervised fine-tuning may lead to overconfident predictions. To address these challenges we propose a two-stage training approach that combines continuous pre-training and supervised fine-tuning. A notable contribution of our study is the processing of a 2GB corpus dedicated to TCM constructing pre-training and instruction fine-tuning datasets for TCM respectively. In addition we have developed Qibo-Benchmark a tool that evaluates the performance of LLM in the TCM on multiple dimensions including subjective objective and three TCM NLP tasks. The medical LLM trained with our pipeline named exhibits significant performance boosts. Compared to the baselines the average subjective win rate is 6337; the average objective accuracy improved by 2337; to 5837; and the Rouge-L scores for the three TCM NLP tasks are 0.72 0.61 and 0.55. Finally we propose a pipline to apply Qibo to TCM consultation and demonstrate the model performance through the case study.
