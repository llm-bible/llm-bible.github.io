---
layout: publication
title: 'QUERT: Continual Pre-training Of Language Model For Query Understanding In Travel Domain Search'
authors: Xie Jian, Liang Yidan, Liu Jingping, Xiao Yanghua, Wu Baohua, Ni Shenghua
conference: "Arxiv"
year: 2023
bibkey: xie2023continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.06707"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
In light of the success of the pre-trained language models (PLMs), continual pre-training of generic PLMs has been the paradigm of domain adaption. In this paper, we propose QUERT, A Continual Pre-trained Language Model for QUERy Understanding in Travel Domain Search. QUERT is jointly trained on four tailored pre-training tasks to the characteristics of query in travel domain search: Geography-aware Mask Prediction, Geohash Code Prediction, User Click Behavior Learning, and Phrase and Token Order Prediction. Performance improvement of downstream tasks and ablation experiment demonstrate the effectiveness of our proposed pre-training tasks. To be specific, the average performance of downstream tasks increases by 2.02&#37; and 30.93&#37; in supervised and unsupervised settings, respectively. To check on the improvement of QUERT to online business, we deploy QUERT and perform A/B testing on Fliggy APP. The feedback results show that QUERT increases the Unique Click-Through Rate and Page Click-Through Rate by 0.89&#37; and 1.03&#37; when applying QUERT as the encoder. Our code and downstream task data will be released for future research.
