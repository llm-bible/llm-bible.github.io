---
layout: publication
title: Multi45;node Bert45;pretraining Cost45;efficient Approach
authors: Lin Jiahuang, Li Xin, Pekhimenko Gennady
conference: "Arxiv"
year: 2020
bibkey: lin2020multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2008.00177"}
tags: ['BERT', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recently large scale Transformer45;based language models such as BERT GPT45;2 and XLNet have brought about exciting leaps in state45;of45;the45;art results for many Natural Language Processing (NLP) tasks. One of the common trends in these recent models is a significant increase in model complexity which introduces both more weights and computation. Moreover with the advent of large45;scale unsupervised datasets training time is further extended due to the increased amount of data samples within a single training epoch. As a result to train these models within a reasonable time machine learning (ML) programmers often require advanced hardware setups such as the premium GPU45;enabled NVIDIA DGX workstations or specialized accelerators such as Googles TPU Pods. Our work addresses this limitation and demonstrates that the BERT pre45;trained model can be trained within 2 weeks on an academic45;size cluster of widely available GPUs through careful algorithmic and software optimizations. In this paper we present these optimizations on how to improve single device training throughput distribute the training workload over multiple nodes and GPUs and overcome the communication bottleneck introduced by the large data exchanges over the network. We show that we are able to perform pre45;training on BERT within a reasonable time budget (12 days) in an academic setting but with a much less expensive and less aggressive hardware resource requirement than in previously demonstrated industrial settings based on NVIDIA DGX machines or Googles TPU Pods.
