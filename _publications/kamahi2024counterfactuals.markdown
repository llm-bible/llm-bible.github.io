---
layout: publication
title: Counterfactuals As a Means for Evaluating Faithfulness of Attribution Methods in Autoregressive Language Models
authors: Kamahi Sepehr, Yaghoobzadeh Yadollah
conference: "Arxiv"
year: 2024
bibkey: kamahi2024counterfactuals
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11252"}
  - {name: "Code", url: "https://github.com/Sepehr-Kamahi/faith"}
tags: ['BERT', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Language Modeling', 'Masked Language Model', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Despite the widespread adoption of autoregressive language models explainability evaluation research has predominantly focused on span infilling and masked language models (MLMs). Evaluating the faithfulness of an explanation method -- how accurately the method explains the inner workings and decision-making of the model -- is very challenging because it is very hard to separate the model from its explanation. Most faithfulness evaluation techniques corrupt or remove some input tokens considered important according to a particular attribution (feature importance) method and observe the change in the models output. This approach creates out-of-distribution inputs for causal language models (CLMs) due to their training objective of next token prediction. In this study we propose a technique that leverages counterfactual generation to evaluate the faithfulness of attribution methods for autoregressive language modeling scenarios. Our technique creates fluent and in-distribution counterfactuals that makes evaluation protocol more reliable. Code is available at https://github.com/Sepehr-Kamahi/faith
