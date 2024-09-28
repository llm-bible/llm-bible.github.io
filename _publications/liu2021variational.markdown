---
layout: publication
title: Variational Latent-State GPT for Semi-Supervised Task-Oriented Dialog Systems
authors: Liu Hong, Cai Yucheng, Lin Zhenru, Ou Zhijian, Huang Yi, Feng Junlan
conference: "Arxiv"
year: 2021
bibkey: liu2021variational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.04314"}
tags: ['Transformer', 'Arxiv', 'Semi-Supervised', 'GPT', 'Supervised', 'Pretraining Methods']
---
Recently two approaches fine-tuning large pre-trained language models and variational training have attracted significant interests separately for semi-supervised end-to-end task-oriented dialog (TOD) systems. In this paper we propose Variational Latent-State GPT model (VLS-GPT) which is the first to combine the strengths of the two approaches. Among many options of models we propose the generative model and the inference model for variational learning of the end-to-end TOD system both as auto-regressive language models based on GPT-2 which can be further trained over a mix of labeled and unlabeled dialog data in a semi-supervised manner. Variational training of VLS-GPT is both statistically and computationally more challenging than previous variational learning works for sequential latent variable models which use turn-level first-order Markovian. The inference model in VLS-GPT is non-Markovian due to the use of the Transformer architecture. In this work we establish Recursive Monte Carlo Approximation (RMCA) to the variational objective with non-Markovian inference model and prove its unbiasedness. Further we develop the computational strategy of sampling-then-forward-computation to realize RMCA which successfully overcomes the memory explosion issue of using GPT in variational learning and speeds up training. Semi-supervised TOD experiments are conducted on two benchmark multi-domain datasets of different languages - MultiWOZ2.1 and CrossWOZ. VLS-GPT is shown to significantly outperform both supervised-only and semi-supervised self-training baselines.
