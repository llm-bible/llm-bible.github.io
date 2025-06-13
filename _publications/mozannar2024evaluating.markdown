---
layout: publication
title: 'The Realhumaneval: Evaluating Large Language Models'' Abilities To Support Programmers'
authors: Hussein Mozannar, Valerie Chen, Mohammed Alsobay, Subhro Das, Sebastian Zhao, Dennis Wei, Manish Nagireddy, Prasanna Sattigeri, Ameet Talwalkar, David Sontag
conference: "Arxiv"
year: 2024
bibkey: mozannar2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.02806'}
tags: ['Reinforcement Learning']
---
Evaluation of large language models for code has primarily relied on static
benchmarks, including HumanEval (Chen et al., 2021), or more recently using
human preferences of LLM responses. As LLMs are increasingly used as programmer
assistants, we study whether gains on existing benchmarks or more preferred LLM
responses translate to programmer productivity when coding with LLMs, including
time spent coding. We introduce RealHumanEval, a web interface to measure the
ability of LLMs to assist programmers, through either autocomplete or chat
support. We conducted a user study (N=243) using RealHumanEval in which users
interacted with seven LLMs of varying base model performance. Despite static
benchmarks not incorporating humans-in-the-loop, we find that improvements in
benchmark performance lead to increased programmer productivity; however gaps
in benchmark versus human performance are not proportional -- a trend that
holds across both forms of LLM support. In contrast, we find that programmer
preferences do not correlate with their actual performance, motivating the need
for better proxy signals. We open-source RealHumanEval to enable human-centric
evaluation of new models and the study data to facilitate efforts to improve
code models.
