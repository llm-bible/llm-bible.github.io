---
layout: publication
title: 'Improving The Efficiency Of Visually Augmented Language Models'
authors: Paula Ontalvilla, Aitor Ormazabal, Gorka Azkune
conference: "Arxiv"
year: 2024
bibkey: ontalvilla2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.11148'}
tags: ['Language Modeling', 'Ethics and Bias', 'Efficiency and Optimization', 'Training Techniques', 'GPT', 'Applications', 'Multimodal Models', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Despite the impressive performance of autoregressive Language Models (LM) it
has been shown that due to reporting bias, LMs lack visual knowledge, i.e. they
do not know much about the visual world and its properties. To augment LMs with
visual knowledge, existing solutions often rely on explicit images, requiring
time-consuming retrieval or image generation systems. This paper shows that
explicit images are not necessary to visually augment an LM. Instead, we use
visually-grounded text representations obtained from the well-known CLIP
multimodal system. For a fair comparison, we modify VALM, a visually-augmented
LM which uses image retrieval and representation, to work directly with
visually-grounded text representations. We name this new model BLIND-VALM. We
show that BLIND-VALM performs on par with VALM for Visual Language
Understanding (VLU), Natural Language Understanding (NLU) and Language Modeling
tasks, despite being significantly more efficient and simpler. We also show
that scaling up our model within the compute budget of VALM, either increasing
the model or pre-training corpus size, we outperform VALM for all the
evaluation tasks.
