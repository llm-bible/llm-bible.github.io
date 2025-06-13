---
layout: publication
title: 'Llmebench: A Flexible Framework For Accelerating Llms Benchmarking'
authors: Fahim Dalvi, Maram Hasanain, Sabri Boughorbel, Basel Mousi, Samir Abdaljalil, Nizi Nazar, Ahmed Abdelali, Shammur Absar Chowdhury, Hamdy Mubarak, Ahmed Ali, Majd Hawasly, Nadir Durrani, Firoj Alam
conference: "Arxiv"
year: 2023
bibkey: dalvi2023flexible
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.04945'}
  - {name: "Code", url: 'https://github.com/qcri/LLMeBench/)'}
  - {name: "Code", url: 'https://youtu.be/9cC2m_abk3A)'}
tags: ['Has Code', 'Few-Shot', 'Tools', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
The recent development and success of Large Language Models (LLMs)
necessitate an evaluation of their performance across diverse NLP tasks in
different languages. Although several frameworks have been developed and made
publicly available, their customization capabilities for specific tasks and
datasets are often complex for different users. In this study, we introduce the
LLMeBench framework, which can be seamlessly customized to evaluate LLMs for
any NLP task, regardless of language. The framework features generic dataset
loaders, several model providers, and pre-implements most standard evaluation
metrics. It supports in-context learning with zero- and few-shot settings. A
specific dataset and task can be evaluated for a given LLM in less than 20
lines of code while allowing full flexibility to extend the framework for
custom datasets, models, or tasks. The framework has been tested on 31 unique
NLP tasks using 53 publicly available datasets within 90 experimental setups,
involving approximately 296K data points. We open-sourced LLMeBench for the
community (https://github.com/qcri/LLMeBench/) and a video demonstrating the
framework is available online. (https://youtu.be/9cC2m_abk3A)
