---
layout: publication
title: 'Persobench: Benchmarking Personalized Response Generation In Large Language Models'
authors: Saleh Afzoon, Usman Naseem, Amin Beheshti, Zahra Jamali
conference: "Arxiv"
year: 2024
bibkey: afzoon2024benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03198'}
  - {name: "Code", url: 'https://github.com/salehafzoon/PersoBench'}
tags: ['Prompting', 'Has Code']
---
While large language models (LLMs) have exhibited impressive conversational
capabilities, their proficiency in delivering personalized responses remains
unclear. Although recent benchmarks automatically evaluate persona consistency
in role-playing contexts using LLM-based judgment, the evaluation of
personalization in response generation remains underexplored. To address this
gap, we present a new benchmark, PersoBench, to evaluate the personalization
ability of LLMs in persona-aware dialogue generation within a zero-shot
setting. We assess the performance of three open-source and three closed-source
LLMs using well-known datasets and a range of metrics. Our analysis, conducted
on three well-known persona-aware datasets, evaluates multiple dimensions of
response quality, including fluency, diversity, coherence, and personalization,
across both standard and chain-of-thought prompting methods. Our findings
reveal that while LLMs excel at generating fluent and diverse responses, they
are far from satisfactory in delivering personalized and coherent responses
considering both the conversation context and the provided personas. Our
benchmark implementation is available at
https://github.com/salehafzoon/PersoBench.
