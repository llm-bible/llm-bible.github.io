---
layout: publication
title: 'Uncovering Cross-domain Recommendation Ability Of Large Language Models'
authors: Xinyi Liu, Ruijie Wang, Dachun Sun, Dilek Hakkani-tur, Tarek Abdelzaher
conference: "LLM4ECommerce Workshop at The Web Conference 2025"
year: 2025
bibkey: liu2025uncovering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07761"}
tags: ['RecSys', 'RAG', 'Prompting', 'Reinforcement Learning']
---
Cross-Domain Recommendation (CDR) seeks to enhance item retrieval in
low-resource domains by transferring knowledge from high-resource domains.
While recent advancements in Large Language Models (LLMs) have demonstrated
their potential in Recommender Systems (RS), their ability to effectively
transfer domain knowledge for improved recommendations remains underexplored.
To bridge this gap, we propose LLM4CDR, a novel CDR pipeline that constructs
context-aware prompts by leveraging users' purchase history sequences from a
source domain along with shared features between source and target domains.
Through extensive experiments, we show that LLM4CDR achieves strong
performance, particularly when using LLMs with large parameter sizes and when
the source and target domains exhibit smaller domain gaps. For instance,
incorporating CD and Vinyl purchase history for recommendations in Movies and
TV yields a 64.28 percent MAP 1 improvement. We further investigate key factors
including source domain data, domain gap, prompt design, and LLM size, which
impact LLM4CDR's effectiveness in CDR tasks. Our results highlight that LLM4CDR
excels when leveraging a single, closely related source domain and benefits
significantly from larger LLMs. These insights pave the way for future research
on LLM-driven cross-domain recommendations.
