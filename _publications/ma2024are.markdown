---
layout: publication
title: Are Large Language Models Good Prompt Optimizers
authors: Ma Ruotian, Wang Xiaolei, Zhou Xin, Li Jian, Du Nan, Gui Tao, Zhang Qi, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: ma2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02101"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Prompting', 'Reinforcement Learning', 'Survey Paper']
---
LLM45;based Automatic Prompt Optimization which typically utilizes LLMs as Prompt Optimizers to self45;reflect and refine prompts has shown promising performance in recent studies. Despite the success the underlying mechanism of this approach remains unexplored and the true effectiveness of LLMs as Prompt Optimizers requires further validation. In this work we conducted a comprehensive study to uncover the actual mechanism of LLM45;based Prompt Optimization. Our findings reveal that the LLM optimizers struggle to identify the true causes of errors during reflection tending to be biased by their own prior knowledge rather than genuinely reflecting on the errors. Furthermore even when the reflection is semantically valid the LLM optimizers often fail to generate appropriate prompts for the target models with a single prompt refinement step partly due to the unpredictable behaviors of the target models. Based on the observations we introduce a new Automatic Behavior Optimization paradigm which directly optimizes the target models behavior in a more controllable manner. We hope our study can inspire new directions for automatic prompt optimization development.
