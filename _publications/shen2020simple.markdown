---
layout: publication
title: A Simple But Tough45;to45;beat Data Augmentation Approach For Natural Language Understanding And Generation
authors: Shen Dinghan, Zheng Mingzhi, Shen Yelong, Qu Yanru, Chen Weizhu
conference: "Arxiv"
year: 2020
bibkey: shen2020simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.13818"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
Adversarial training has been shown effective at endowing the learned representations with stronger generalization ability. However it typically requires expensive computation to determine the direction of the injected perturbations. In this paper we introduce a set of simple yet effective data augmentation strategies dubbed cutoff where part of the information within an input sentence is erased to yield its restricted views (during the fine45;tuning stage). Notably this process relies merely on stochastic sampling and thus adds little computational overhead. A Jensen45;Shannon Divergence consistency loss is further utilized to incorporate these augmented samples into the training objective in a principled manner. To verify the effectiveness of the proposed strategies we apply cutoff to both natural language understanding and generation problems. On the GLUE benchmark it is demonstrated that cutoff in spite of its simplicity performs on par or better than several competitive adversarial45;based approaches. We further extend cutoff to machine translation and observe significant gains in BLEU scores (based upon the Transformer Base model). Moreover cutoff consistently outperforms adversarial training and achieves state45;of45;the45;art results on the IWSLT2014 German45;English dataset.
