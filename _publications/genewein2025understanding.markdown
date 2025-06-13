---
layout: publication
title: 'Understanding Prompt Tuning And In-context Learning Via Meta-learning'
authors: Tim Genewein, Kevin Wenliang Li, Jordi Grau-moya, Anian Ruoss, Laurent Orseau, Marcus Hutter
conference: "Arxiv"
year: 2025
bibkey: genewein2025understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17010"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Prompting', 'In-Context Learning']
---
Prompting is one of the main ways to adapt a pretrained model to target tasks. Besides manually constructing prompts, many prompt optimization methods have been proposed in the literature. Method development is mainly empirically driven, with less emphasis on a conceptual understanding of prompting. In this paper we discuss how optimal prompting can be understood through a Bayesian view, which also implies some fundamental limitations of prompting that can only be overcome by tuning weights. The paper explains in detail how meta-trained neural networks behave as Bayesian predictors over the pretraining distribution, whose hallmark feature is rapid in-context adaptation. Optimal prompting can be studied formally as conditioning these Bayesian predictors, yielding criteria for target tasks where optimal prompting is and is not possible. We support the theory with educational experiments on LSTMs and Transformers, where we compare different versions of prefix-tuning and different weight-tuning methods. We also confirm that soft prefixes, which are sequences of real-valued vectors outside the token alphabet, can lead to very effective prompts for trained and even untrained networks by manipulating activations in ways that are not achievable by hard tokens. This adds an important mechanistic aspect beyond the conceptual Bayesian theory.
