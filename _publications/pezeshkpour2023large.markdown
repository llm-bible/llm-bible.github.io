---
layout: publication
title: Large Language Models Sensitivity To The Order Of Options In Multiple45;choice Questions
authors: Pezeshkpour Pouya, Hruschka Estevam
conference: "Arxiv"
year: 2023
bibkey: pezeshkpour2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11483"}
tags: ['Ethics And Bias', 'Prompting', 'Security']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in various NLP tasks. However previous works have shown these models are sensitive towards prompt wording and few45;shot demonstrations and their order posing challenges to fair assessment of these models. As these models become more powerful it becomes imperative to understand and address these limitations. In this paper we focus on LLMs robustness on the task of multiple45;choice questions 45;45; commonly adopted task to study reasoning and fact45;retrieving capability of LLMs. Investigating the sensitivity of LLMs towards the order of options in multiple45;choice questions we demonstrate a considerable performance gap of approximately 1337; to 7537; in LLMs on different benchmarks when answer options are reordered even when using demonstrations in a few45;shot setting. Through a detailed analysis we conjecture that this sensitivity arises when LLMs are uncertain about the prediction between the top45;2/3 choices and specific options placements may favor certain prediction between those top choices depending on the question caused by positional bias. We also identify patterns in top45;2 choices that amplify or mitigate the models bias toward option placement. We found that for amplifying bias the optimal strategy involves positioning the top two choices as the first and last options. Conversely to mitigate bias we recommend placing these choices among the adjacent options. To validate our conjecture we conduct various experiments and adopt two approaches to calibrate LLMs predictions leading to up to 8 percentage points improvement across different models and benchmarks.
