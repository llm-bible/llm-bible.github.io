---
layout: publication
title: 'P\(^2\) Law: Scaling Law For Post-training After Model Pruning'
authors: Xiaodong Chen, Yuxuan Hu, Xiaokang Zhang, Yanling Wang, Cuiping Li, Hong Chen, Jing Zhang
conference: "Arxiv"
year: 2024
bibkey: chen2024scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.10272'}
tags: ['Pruning', 'Efficiency and Optimization', 'Training Techniques']
---
Pruning has become a widely adopted technique for reducing the hardware requirements of large language models (LLMs). To recover model performance after pruning, post-training is commonly employed to mitigate the resulting performance degradation. While post-training benefits from larger datasets, once the dataset size is already substantial, increasing the training data provides only limited performance gains. To balance post-training cost and model performance, it is necessary to explore the optimal amount of post-training data.Through extensive experiments on the Llama-3 and Qwen-2.5 series models, pruned using various common pruning methods, we uncover the scaling \textbf\{Law\} for \textbf\{P\}ost-training after model \textbf\{P\}runing, referred to as the P\\(^2\\) Law.This law identifies four key factors for predicting the pruned model's post-training loss: the model size before pruning, the number of post-training tokens, the pruning rate, and the model's loss before pruning. Moreover, P\\(^2\\) Law can generalize to larger dataset sizes, larger model sizes, and higher pruning rates, offering valuable insights for the post-training of pruned LLMs.
