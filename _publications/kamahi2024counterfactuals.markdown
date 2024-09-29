---
layout: publication
title: Counterfactuals As A Means For Evaluating Faithfulness Of Attribution Methods In Autoregressive Language Models
authors: Kamahi Sepehr, Yaghoobzadeh Yadollah
conference: "Arxiv"
year: 2024
bibkey: kamahi2024counterfactuals
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11252"}
  - {name: "Code", url: "https://github.com/Sepehr&#45;Kamahi/faith"}
tags: ['BERT', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Language Modeling', 'Masked Language Model', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Despite the widespread adoption of autoregressive language models explainability evaluation research has predominantly focused on span infilling and masked language models (MLMs). Evaluating the faithfulness of an explanation method 45;45; how accurately the method explains the inner workings and decision45;making of the model 45;45; is very challenging because it is very hard to separate the model from its explanation. Most faithfulness evaluation techniques corrupt or remove some input tokens considered important according to a particular attribution (feature importance) method and observe the change in the models output. This approach creates out45;of45;distribution inputs for causal language models (CLMs) due to their training objective of next token prediction. In this study we propose a technique that leverages counterfactual generation to evaluate the faithfulness of attribution methods for autoregressive language modeling scenarios. Our technique creates fluent and in45;distribution counterfactuals that makes evaluation protocol more reliable. Code is available at https://github.com/Sepehr&#45;Kamahi/faith
