---
layout: publication
title: 'Comfygen: Prompt-adaptive Workflows For Text-to-image Generation'
authors: Rinon Gal, Adi Haviv, Yuval Alaluf, Amit H. Bermano, Daniel Cohen-or, Gal Chechik
conference: "Arxiv"
year: 2024
bibkey: gal2024prompt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.01731'}
tags: ['Prompting', 'Training Techniques']
---
The practical use of text-to-image generation has evolved from simple,
monolithic models to complex workflows that combine multiple specialized
components. While workflow-based approaches can lead to improved image quality,
crafting effective workflows requires significant expertise, owing to the large
number of available components, their complex inter-dependence, and their
dependence on the generation prompt. Here, we introduce the novel task of
prompt-adaptive workflow generation, where the goal is to automatically tailor
a workflow to each user prompt. We propose two LLM-based approaches to tackle
this task: a tuning-based method that learns from user-preference data, and a
training-free method that uses the LLM to select existing flows. Both
approaches lead to improved image quality when compared to monolithic models or
generic, prompt-independent workflows. Our work shows that prompt-dependent
flow prediction offers a new pathway to improving text-to-image generation
quality, complementing existing research directions in the field.
