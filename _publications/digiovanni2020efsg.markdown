---
layout: publication
title: EFSG Evolutionary Fooling Sentences Generator
authors: Di Giovanni Marco, Brambilla Marco
conference: "Arxiv"
year: 2020
bibkey: digiovanni2020efsg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.05736"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Security', 'Training Techniques']
---
Large pre-trained language representation models (LMs) have recently collected a huge number of successes in many NLP tasks. In 2018 BERT and later its successors (e.g. RoBERTa) obtained state-of-the-art results in classical benchmark tasks such as GLUE benchmark. After that works about adversarial attacks have been published to test their generalization proprieties and robustness. In this work we design Evolutionary Fooling Sentences Generator (EFSG) a model- and task-agnostic adversarial attack algorithm built using an evolutionary approach to generate false-positive sentences for binary classification tasks. We successfully apply EFSG to CoLA and MRPC tasks on BERT and RoBERTa comparing performances. Results prove the presence of weak spots in state-of-the-art LMs. We finally test adversarial training as a data augmentation defence approach against EFSG obtaining stronger improved models with no loss of accuracy when tested on the original datasets.
