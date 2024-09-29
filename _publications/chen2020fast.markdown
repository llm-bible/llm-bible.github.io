---
layout: publication
title: "Dipair: Fast And Accurate Distillation For Trillion-scale Text Matching And Pair Modeling"
authors: Chen Jiecao, Yang Liu, Raman Karthik, Bendersky Michael, Yeh Jung-jung, Zhou Yun, Najork Marc, Cai Danyang, Emadzadeh Ehsan
conference: "Arxiv"
year: 2020
bibkey: chen2020fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.03099"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Pre-trained models like BERT (Devlin et al. 2018) have dominated NLP / IR applications such as single sentence classification text pair classification and question answering. However deploying these models in real systems is highly non-trivial due to their exorbitant computational costs. A common remedy to this is knowledge distillation (Hinton et al. 2015) leading to faster inference. However -- as we show here -- existing works are not optimized for dealing with pairs (or tuples) of texts. Consequently they are either not scalable or demonstrate subpar performance. In this work we propose DiPair -- a novel framework for distilling fast and accurate models on text pair tasks. Coupled with an end-to-end training strategy DiPair is both highly scalable and offers improved quality-speed tradeoffs. Empirical studies conducted on both academic and real-world e-commerce benchmarks demonstrate the efficacy of the proposed approach with speedups of over 350x and minimal quality drop relative to the cross-attention teacher BERT model.
