---
layout: publication
title: 'GPT-D: Inducing Dementia-related Linguistic Anomalies By Deliberate Degradation Of Artificial Neural Language Models'
authors: Li Changye, Knopman David, Xu Weizhe, Cohen Trevor, Pakhomov Serguei
conference: "Arxiv"
year: 2022
bibkey: li2022gpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.13397"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Deep learning (DL) techniques involving fine-tuning large numbers of model
parameters have delivered impressive performance on the task of discriminating
between language produced by cognitively healthy individuals, and those with
Alzheimer's disease (AD). However, questions remain about their ability to
generalize beyond the small reference sets that are publicly available for
research. As an alternative to fitting model parameters directly, we propose a
novel method by which a Transformer DL model (GPT-2) pre-trained on general
English text is paired with an artificially degraded version of itself (GPT-D),
to compute the ratio between these two models' \textit\{perplexities\} on
language from cognitively healthy and impaired individuals. This technique
approaches state-of-the-art performance on text data from a widely used "Cookie
Theft" picture description task, and unlike established alternatives also
generalizes well to spontaneous conversations. Furthermore, GPT-D generates
text with characteristics known to be associated with AD, demonstrating the
induction of dementia-related linguistic anomalies. Our study is a step toward
better understanding of the relationships between the inner workings of
generative neural language models, the language that they produce, and the
deleterious effects of dementia on human speech and language characteristics.
