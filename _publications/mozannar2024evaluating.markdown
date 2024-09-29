---
layout: publication
title: The Realhumaneval Evaluating Large Language Models Abilities To Support Programmers
authors: Mozannar Hussein, Chen Valerie, Alsobay Mohammed, Das Subhro, Zhao Sebastian, Wei Dennis, Nagireddy Manish, Sattigeri Prasanna, Talwalkar Ameet, Sontag David
conference: "Arxiv"
year: 2024
bibkey: mozannar2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02806"}
tags: ['Ethics And Bias', 'Reinforcement Learning']
---
Evaluation of large language models (LLMs) for code has primarily relied on static benchmarks including HumanEval (Chen et al. 2021) which measure the ability of LLMs to generate complete code that passes unit tests. As LLMs are increasingly used as programmer assistants we study whether gains on existing benchmarks translate to gains in programmer productivity when coding with LLMs including time spent coding. In addition to static benchmarks we investigate the utility of preference metrics that might be used as proxies to measure LLM helpfulness such as code acceptance or copy rates. To do so we introduce RealHumanEval a web interface to measure the ability of LLMs to assist programmers through either autocomplete or chat support. We conducted a user study (N=213) using RealHumanEval in which users interacted with six LLMs of varying base model performance. Despite static benchmarks not incorporating humans-in-the-loop we find that improvements in benchmark performance lead to increased programmer productivity; however gaps in benchmark versus human performance are not proportional -- a trend that holds across both forms of LLM support. In contrast we find that programmer preferences do not correlate with their actual performance motivating the need for better human-centric proxy signals. We also open-source RealHumanEval to enable human-centric evaluation of new models and the study data to facilitate efforts to improve code models.
