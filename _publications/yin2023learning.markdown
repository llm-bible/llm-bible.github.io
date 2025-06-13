---
layout: publication
title: 'Learning Globally Optimized Language Structure Via Adversarial Training'
authors: Xuwang Yin
conference: "Arxiv"
year: 2023
bibkey: yin2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06771"}
tags: ['Security', 'Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'GPT', 'Pretraining Methods', 'Applications']
---
Recent work has explored integrating autoregressive language models with
energy-based models (EBMs) to enhance text generation capabilities. However,
learning effective EBMs for text is challenged by the discrete nature of
language. This work proposes an adversarial training strategy to address
limitations in prior efforts. Specifically, an iterative adversarial attack
algorithm is presented to generate negative samples for training the EBM by
perturbing text from the autoregressive model. This aims to enable the EBM to
suppress spurious modes outside the support of the data distribution.
Experiments on an arithmetic sequence generation task demonstrate that the
proposed adversarial training approach can substantially enhance the quality of
generated sequences compared to prior methods. The results highlight the
promise of adversarial techniques to improve discrete EBM training. Key
contributions include: (1) an adversarial attack strategy tailored to text to
generate negative samples, circumventing MCMC limitations; (2) an adversarial
training algorithm for EBMs leveraging these attacks; (3) empirical validation
of performance improvements on a sequence generation task.
