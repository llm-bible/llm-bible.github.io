---
layout: publication
title: Well45;read Students Learn Better On The Importance Of Pre45;training Compact Models
authors: Turc Iulia, Chang Ming-wei, Lee Kenton, Toutanova Kristina
conference: "Arxiv"
year: 2019
bibkey: turc2019well
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1908.08962"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Quantization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recent developments in natural language representations have been accompanied by large and expensive models that leverage vast amounts of general45;domain text through self45;supervised pre45;training. Due to the cost of applying such models to down45;stream tasks several model compression techniques on pre45;trained language representations have been proposed (Sun et al. 2019; Sanh 2019). However surprisingly the simple baseline of just pre45;training and fine45;tuning compact models has been overlooked. In this paper we first show that pre45;training remains important in the context of smaller architectures and fine45;tuning pre45;trained compact models can be competitive to more elaborate methods proposed in concurrent work. Starting with pre45;trained compact models we then explore transferring task knowledge from large fine45;tuned models through standard knowledge distillation. The resulting simple yet effective and general algorithm Pre45;trained Distillation brings further improvements. Through extensive experiments we more generally explore the interaction between pre45;training and distillation under two variables that have been under45;studied model size and properties of unlabeled task data. One surprising observation is that they have a compound effect even when sequentially applied on the same data. To accelerate future research we will make our 24 pre45;trained miniature BERT models publicly available.
