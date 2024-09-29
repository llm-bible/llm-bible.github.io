---
layout: publication
title: An Empirical Study On Cross45;lingual Vocabulary Adaptation For Efficient Language Model Inference
authors: Yamaguchi Atsuki, Villavicencio Aline, Aletras Nikolaos
conference: "Arxiv"
year: 2024
bibkey: yamaguchi2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10712"}
tags: ['Applications', 'Efficiency And Optimization', 'Training Techniques']
---
The development of state45;of45;the45;art generative large language models (LLMs) disproportionately relies on English45;centric tokenizers vocabulary and pre45;training data. Despite the fact that some LLMs have multilingual capabilities recent studies have shown that their inference efficiency deteriorates when generating text in languages other than English. This results in increased inference time and costs. Cross45;lingual vocabulary adaptation (CVA) methods have been proposed for adapting models to a target language aiming to improve downstream performance. However the effectiveness of these methods on increasing inference efficiency of generative LLMs has yet to be explored. In this paper we perform an empirical study of five CVA methods on four generative LLMs (including monolingual and multilingual models) across four typologically45;diverse languages and four natural language understanding tasks. We find that CVA substantially contributes to LLM inference speedups of up to 271.537;. We also show that adapting LLMs that have been pre45;trained on more balanced multilingual data results in downstream performance comparable to the original models.
