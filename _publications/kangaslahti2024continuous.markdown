---
layout: publication
title: "Continuous Language Model Interpolation For Dynamic And Controllable Text Generation"
authors: Kangaslahti Sara, Alvarez-melis David
conference: "Arxiv"
year: 2024
bibkey: kangaslahti2024continuous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07117"}
tags: ['Applications', 'Language Modeling', 'RAG', 'Reinforcement Learning']
---
As large language models (LLMs) have gained popularity for a variety of use cases making them adaptable and controllable has become increasingly important especially for user-facing applications. While the existing literature on LLM adaptation primarily focuses on finding a model (or models) that optimizes a single predefined objective here we focus on the challenging case where the model must dynamically adapt to diverse -- and often changing -- user preferences. For this we leverage adaptation methods based on linear weight interpolation casting them as continuous multi-domain interpolators that produce models with specific prescribed generation characteristics on-the-fly. Specifically we use low-rank updates to fine-tune a base model to various different domains yielding a set of anchor models with distinct generation profiles. Then we use the weight updates of these anchor models to parametrize the entire (infinite) class of models contained within their convex hull. We empirically show that varying the interpolation weights yields predictable and consistent change in the model outputs with respect to all of the controlled attributes. We find that there is little entanglement between most attributes and identify and discuss the pairs of attributes for which this is not the case. Our results suggest that linearly interpolating between the weights of fine-tuned models facilitates predictable fine-grained control of model outputs with respect to multiple stylistic characteristics simultaneously.
