---
layout: publication
title: An Understanding-Oriented Robust Machine Reading Comprehension Model
authors: Ren Feiliang, Liu Yongkang, Li Bochao, Liu Shilei, Wang Bingchao, Wang Jiaqi, Liu Chunchao, Ma Qi
conference: "Arxiv"
year: 2022
bibkey: ren2022understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.00187"}
  - {name: "Code", url: "https://github.com/neukg/RobustMRC"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Security', 'Tools']
---
Although existing machine reading comprehension models are making rapid progress on many datasets they are far from robust. In this paper we propose an understanding-oriented machine reading comprehension model to address three kinds of robustness issues which are over sensitivity over stability and generalization. Specifically we first use a natural language inference module to help the model understand the accurate semantic meanings of input questions so as to address the issues of over sensitivity and over stability. Then in the machine reading comprehension module we propose a memory-guided multi-head attention method that can further well understand the semantic meanings of input questions and passages. Third we propose a multilanguage learning mechanism to address the issue of generalization. Finally these modules are integrated with a multi-task learning based method. We evaluate our model on three benchmark datasets that are designed to measure models robustness including DuReader (robust) and two SQuAD-related datasets. Extensive experiments show that our model can well address the mentioned three kinds of robustness issues. And it achieves much better results than the compared state-of-the-art models on all these datasets under different evaluation metrics even under some extreme and unfair evaluations. The source code of our work is available at https://github.com/neukg/RobustMRC.
