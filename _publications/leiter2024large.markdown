---
layout: publication
title: 'Prexme! Large Scale Prompt Exploration Of Open Source Llms For Machine Translation And Summarization Evaluation'
authors: Christoph Leiter, Steffen Eger
conference: "Arxiv"
year: 2024
bibkey: leiter2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.18528'}
tags: ['Applications', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Large language models (LLMs) have revolutionized NLP research. Notably,
in-context learning enables their use as evaluation metrics for natural
language generation, making them particularly advantageous in low-resource
scenarios and time-restricted applications. In this work, we introduce PrExMe,
a large-scale Prompt Exploration for Metrics, where we evaluate more than 720
prompt templates for open-source LLM-based metrics on machine translation (MT)
and summarization datasets, totalling over 6.6M evaluations. This extensive
comparison (1) benchmarks recent open-source LLMs as metrics and (2) explores
the stability and variability of different prompting strategies. We discover
that, on the one hand, there are scenarios for which prompts are stable. For
instance, some LLMs show idiosyncratic preferences and favor to grade generated
texts with textual labels while others prefer to return numeric scores. On the
other hand, the stability of prompts and model rankings can be susceptible to
seemingly innocuous changes. For example, changing the requested output format
from "0 to 100" to "-1 to +1" can strongly affect the rankings in our
evaluation. Our study contributes to understanding the impact of different
prompting approaches on LLM-based metrics for MT and summarization evaluation,
highlighting the most stable prompting patterns and potential limitations.
