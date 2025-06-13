---
layout: publication
title: 'Don''t Use Llms To Make Relevance Judgments'
authors: Ian Soboroff
conference: "Information Retrieval Research. 1 1 (Mar. 2025) 29-46"
year: 2024
bibkey: soboroff2024use
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15133'}
tags: ['SIGIR', 'Arxiv', 'Reinforcement Learning', 'Prompting']
---
Making the relevance judgments for a TREC-style test collection can be
complex and expensive. A typical TREC track usually involves a team of six
contractors working for 2-4 weeks. Those contractors need to be trained and
monitored. Software has to be written to support recording relevance judgments
correctly and efficiently. The recent advent of large language models that
produce astoundingly human-like flowing text output in response to a natural
language prompt has inspired IR researchers to wonder how those models might be
used in the relevance judgment collection process. At the ACM SIGIR 2024
conference, a workshop ``LLM4Eval'' provided a venue for this work, and
featured a data challenge activity where participants reproduced TREC deep
learning track judgments, as was done by Thomas et al (arXiv:2408.08896,
arXiv:2309.10621). I was asked to give a keynote at the workshop, and this
paper presents that keynote in article form. The bottom-line-up-front message
is, don't use LLMs to create relevance judgments for TREC-style evaluations.
