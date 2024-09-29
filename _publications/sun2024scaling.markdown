---
layout: publication
title: Scaling Behavior Of Machine Translation With Large Language Models Under Prompt Injection Attacks
authors: Sun Zhifan, Miceli-barone Antonio Valerio
conference: "Arxiv"
year: 2024
bibkey: sun2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09832"}
tags: ['Applications', 'Prompting', 'Security', 'Tools']
---
Large Language Models (LLMs) are increasingly becoming the preferred foundation platforms for many Natural Language Processing tasks such as Machine Translation owing to their quality often comparable to or better than task-specific models and the simplicity of specifying the task through natural language instructions or in-context examples. Their generality however opens them up to subversion by end users who may embed into their requests instructions that cause the model to behave in unauthorized and possibly unsafe ways. In this work we study these Prompt Injection Attacks (PIAs) on multiple families of LLMs on a Machine Translation task focusing on the effects of model size on the attack success rates. We introduce a new benchmark data set and we discover that on multiple language pairs and injected prompts written in English larger models under certain conditions may become more susceptible to successful attacks an instance of the Inverse Scaling phenomenon (McKenzie et al. 2023). To our knowledge this is the first work to study non-trivial LLM scaling behaviour in a multi-lingual setting.
