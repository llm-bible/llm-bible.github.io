---
layout: publication
title: Self45;supervised Meta45;prompt Learning With Meta45;gradient Regularization For Few45;shot Generalization
authors: Pan Kaihang, Li Juncheng, Song Hongye, Lin Jun, Liu Xiaozhong, Tang Siliang
conference: "Arxiv"
year: 2023
bibkey: pan2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.12314"}
  - {name: "Code", url: "https://github.com/beepkh/SUPMER"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Prompt tuning is a parameter45;efficient method which learns soft prompts and conditions frozen language models to perform specific downstream tasks. Though effective prompt tuning under few45;shot settings on the one hand heavily relies on a good initialization of soft prompts. On the other hand it can easily overfit to few45;shot training samples thereby undermining generalizability. Existing works leverage pre45;training or supervised meta45;learning to initialize soft prompts but they fail to data45;efficiently generalize to unseen downstream tasks. To address the above problems this paper proposes a novel Self45;sUpervised meta45;Prompt learning framework with MEta45;gradient Regularization for few45;shot generalization (SUPMER). SUPMER leverages self45;supervised meta45;learning with a diverse set of well45;designed meta45;training tasks to learn a universal prompt initialization for efficient adaptation using only unlabeled data. Additionally it jointly meta45;learns a gradient regularization function to transform raw gradients into a domain45;generalizable direction thus alleviating the problem of overfitting. Extensive experiments show that SUPMER achieves better performance for different few45;shot downstream tasks and also exhibits a stronger domain generalization ability. The code for SUPMER will be available at https://github.com/beepkh/SUPMER.
