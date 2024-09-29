---
layout: publication
title: Dipair Fast And Accurate Distillation For Trillion45;scale Text Matching And Pair Modeling
authors: Chen Jiecao, Yang Liu, Raman Karthik, Bendersky Michael, Yeh Jung-jung, Zhou Yun, Najork Marc, Cai Danyang, Emadzadeh Ehsan
conference: "Arxiv"
year: 2020
bibkey: chen2020fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.03099"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Pre45;trained models like BERT (Devlin et al. 2018) have dominated NLP / IR applications such as single sentence classification text pair classification and question answering. However deploying these models in real systems is highly non45;trivial due to their exorbitant computational costs. A common remedy to this is knowledge distillation (Hinton et al. 2015) leading to faster inference. However 45;45; as we show here 45;45; existing works are not optimized for dealing with pairs (or tuples) of texts. Consequently they are either not scalable or demonstrate subpar performance. In this work we propose DiPair 45;45; a novel framework for distilling fast and accurate models on text pair tasks. Coupled with an end45;to45;end training strategy DiPair is both highly scalable and offers improved quality45;speed tradeoffs. Empirical studies conducted on both academic and real45;world e45;commerce benchmarks demonstrate the efficacy of the proposed approach with speedups of over 350x and minimal quality drop relative to the cross45;attention teacher BERT model.
