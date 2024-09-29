---
layout: publication
title: "CPM: A Large-scale Generative Chinese Pre-trained Language Model"
authors: Zhang Zhengyan, Han Xu, Zhou Hao, Ke Pei, Gu Yuxian, Ye Deming, Qin Yujia, Su Yusheng, Ji Haozhe, Guan Jian, Qi Fanchao, Wang Xiaozhi, Zheng Yanan, Zeng Guoyang, Cao Huanqi, Chen Shengqi, Li Daixuan, Sun Zhenbo, Liu Zhiyuan, Huang Minlie, Han Wentao, Tang Jie, Li Juanzi, Zhu Xiaoyan, Sun Maosong
conference: "Arxiv"
year: 2020
bibkey: zhang2020large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.00413"}
  - {name: "Code", url: "https://github.com/TsinghuaAI/CPM-Generate"}
tags: ['Attention Mechanism', 'Few Shot', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Pre-trained Language Models (PLMs) have proven to be beneficial for various downstream NLP tasks. Recently GPT-3 with 175 billion parameters and 570GB training data drew a lot of attention due to the capacity of few-shot (even zero-shot) learning. However applying GPT-3 to address Chinese NLP tasks is still challenging as the training corpus of GPT-3 is primarily English and the parameters are not publicly available. In this technical report we release the Chinese Pre-trained Language Model (CPM) with generative pre-training on large-scale Chinese training data. To the best of our knowledge CPM with 2.6 billion parameters and 100GB Chinese training data is the largest Chinese pre-trained language model which could facilitate several downstream Chinese NLP tasks such as conversation essay generation cloze test and language understanding. Extensive experiments demonstrate that CPM achieves strong performance on many NLP tasks in the settings of few-shot (even zero-shot) learning. The code and parameters are available at https://github.com/TsinghuaAI/CPM-Generate."
