---
layout: publication
title: 'Optimizing Low-resource Language Model Training: Comprehensive Analysis Of Multi-epoch, Multi-lingual, And Two-stage Approaches'
authors: Kosuke Akimoto, Masafumi Oyamada
conference: "Arxiv"
year: 2024
bibkey: akimoto2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12325"}
tags: ['Training Techniques']
---
In this paper, we address the challenge of optimizing training setups for
Large Language Models (LLMs) of low-resource language with a limited amount of
corpus. Existing works adopt multi-epoch, multi-lingual, and two-stage training
to utilize the limited target language corpus efficiently. However, there is
still a lack of understanding about the optimal hyperparameter setups for
combining these three approaches to train LLMs. We exhaustively explore
training setups for low-resource language LLM, combining these three
approaches, and found the following insights for efficiently reducing the cost
of hyperparameter search: (1) As the amount of target language corpus
decreases, the optimal training approach shifts from monolingual single-stage
training to multi-lingual two-stage training at a compute budget dependent
threshold. (2) The optimal model scale remains stable regardless of the amount
of target language corpus, allowing the use of the compute-optimal scale of
monolingual training. (3) The optimal number of epochs can be extrapolated from
smaller-scale experiments to larger scale using our proposed model. Also, we
provide evidence that, in single-stage training, the target language validation
loss follows a power law with respect to the target language ratio, with an
exponent independent of the amount of data, model scale, and language pair.
