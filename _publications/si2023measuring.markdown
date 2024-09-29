---
layout: publication
title: "Measuring Inductive Biases Of In-context Learning With Underspecified Demonstrations"
authors: Si Chenglei, Friedman Dan, Joshi Nitish, Feng Shi, Chen Danqi, He He
conference: "Arxiv"
year: 2023
bibkey: si2023measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13299"}
tags: ['Ethics And Bias', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
In-context learning (ICL) is an important paradigm for adapting large language models (LLMs) to new tasks but the generalization behavior of ICL remains poorly understood. We investigate the inductive biases of ICL from the perspective of feature bias which feature ICL is more likely to use given a set of underspecified demonstrations in which two features are equally predictive of the labels. First we characterize the feature biases of GPT-3 models by constructing underspecified demonstrations from a range of NLP datasets and feature combinations. We find that LLMs exhibit clear feature biases - for example demonstrating a strong bias to predict labels according to sentiment rather than shallow lexical features like punctuation. Second we evaluate the effect of different interventions that are designed to impose an inductive bias in favor of a particular feature such as adding a natural language instruction or using semantically relevant label words. We find that while many interventions can influence the learner to prefer a particular feature it can be difficult to overcome strong prior biases. Overall our results provide a broader picture of the types of features that ICL may be more likely to exploit and how to impose inductive biases that are better aligned with the intended task.
