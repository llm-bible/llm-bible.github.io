---
layout: publication
title: 'Counterfactuals As A Means For Evaluating Faithfulness Of Attribution Methods In Autoregressive Language Models'
authors: Sepehr Kamahi, Yadollah Yaghoobzadeh
conference: "Arxiv"
year: 2024
bibkey: kamahi2024counterfactuals
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.11252'}
tags: ['Masked Language Model', 'Interpretability and Explainability', 'RAG', 'GPT', 'BERT', 'Training Techniques', 'Interpretability', 'Pretraining Methods']
---
Despite the widespread adoption of autoregressive language models,
explainability evaluation research has predominantly focused on span infilling
and masked language models. Evaluating the faithfulness of an explanation
method -- how accurately it explains the inner workings and decision-making of
the model -- is challenging because it is difficult to separate the model from
its explanation. Most faithfulness evaluation techniques corrupt or remove
input tokens deemed important by a particular attribution (feature importance)
method and observe the resulting change in the model's output. However, for
autoregressive language models, this approach creates out-of-distribution
inputs due to their next-token prediction training objective. In this study, we
propose a technique that leverages counterfactual generation to evaluate the
faithfulness of attribution methods for autoregressive language models. Our
technique generates fluent, in-distribution counterfactuals, making the
evaluation protocol more reliable.
