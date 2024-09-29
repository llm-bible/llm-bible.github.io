---
layout: publication
title: Variational Latent45;state GPT For Semi45;supervised Task45;oriented Dialog Systems
authors: Liu Hong, Cai Yucheng, Lin Zhenru, Ou Zhijian, Huang Yi, Feng Junlan
conference: "Arxiv"
year: 2021
bibkey: liu2021variational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.04314"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recently two approaches fine45;tuning large pre45;trained language models and variational training have attracted significant interests separately for semi45;supervised end45;to45;end task45;oriented dialog (TOD) systems. In this paper we propose Variational Latent45;State GPT model (VLS45;GPT) which is the first to combine the strengths of the two approaches. Among many options of models we propose the generative model and the inference model for variational learning of the end45;to45;end TOD system both as auto45;regressive language models based on GPT45;2 which can be further trained over a mix of labeled and unlabeled dialog data in a semi45;supervised manner. Variational training of VLS45;GPT is both statistically and computationally more challenging than previous variational learning works for sequential latent variable models which use turn45;level first45;order Markovian. The inference model in VLS45;GPT is non45;Markovian due to the use of the Transformer architecture. In this work we establish Recursive Monte Carlo Approximation (RMCA) to the variational objective with non45;Markovian inference model and prove its unbiasedness. Further we develop the computational strategy of sampling45;then45;forward45;computation to realize RMCA which successfully overcomes the memory explosion issue of using GPT in variational learning and speeds up training. Semi45;supervised TOD experiments are conducted on two benchmark multi45;domain datasets of different languages 45; MultiWOZ2.1 and CrossWOZ. VLS45;GPT is shown to significantly outperform both supervised45;only and semi45;supervised self45;training baselines.
