---
layout: publication
title: AD45;DROP Attribution45;driven Dropout For Robust Language Model Fine45;tuning
authors: Yang Tao, Deng Jinghao, Quan Xiaojun, Wang Qifan, Nie Shaoliang
conference: "Arxiv"
year: 2022
bibkey: yang2022ad
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.05883"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Training Techniques', 'Transformer']
---
Fine45;tuning large pre45;trained language models on downstream tasks is apt to suffer from overfitting when limited training data is available. While dropout proves to be an effective antidote by randomly dropping a proportion of units existing research has not examined its effect on the self45;attention mechanism. In this paper we investigate this problem through self45;attention attribution and find that dropping attention positions with low attribution scores can accelerate training and increase the risk of overfitting. Motivated by this observation we propose Attribution45;Driven Dropout (AD45;DROP) which randomly discards some high45;attribution positions to encourage the model to make predictions by relying more on low45;attribution positions to reduce overfitting. We also develop a cross45;tuning strategy to alternate fine45;tuning and AD45;DROP to avoid dropping high45;attribution positions excessively. Extensive experiments on various benchmarks show that AD45;DROP yields consistent improvements over baselines. Analysis further confirms that AD45;DROP serves as a strategic regularizer to prevent overfitting during fine45;tuning.
