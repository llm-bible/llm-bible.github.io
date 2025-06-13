---
layout: publication
title: 'Push The Limit Of Multi-modal Emotion Recognition By Prompting Llms With Receptive-field-aware Attention Weighting'
authors: Liyun Zhang, Dian Ding, Yu Lu, Yi-chao Chen, Guangtao Xue
conference: "Arxiv"
year: 2024
bibkey: zhang2024push
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17674"}
tags: ['Model Architecture', 'Tools', 'GPT', 'Prompting', 'Attention Mechanism']
---
Understanding the emotions in a dialogue usually requires external knowledge
to accurately understand the contents. As the LLMs become more and more
powerful, we do not want to settle on the limited ability of the pre-trained
language model. However, the LLMs either can only process text modality or are
too expensive to process the multimedia information. We aim to utilize both the
power of LLMs and the supplementary features from the multimedia modalities. In
this paper, we present a framework, Lantern, that can improve the performance
of a certain vanilla model by prompting large language models with
receptive-field-aware attention weighting. This framework trained a multi-task
vanilla model to produce probabilities of emotion classes and dimension scores.
These predictions are fed into the LLMs as references to adjust the predicted
probabilities of each emotion class with its external knowledge and contextual
understanding. We slice the dialogue into different receptive fields, and each
sample is included in exactly t receptive fields. Finally, the predictions of
LLMs are merged with a receptive-field-aware attention-driven weighting module.
In the experiments, vanilla models CORECT and SDT are deployed in Lantern with
GPT-4 or Llama-3.1-405B. The experiments in IEMOCAP with 4-way and 6-way
settings demonstrated that the Lantern can significantly improve the
performance of current vanilla models by up to 1.23% and 1.80%.
