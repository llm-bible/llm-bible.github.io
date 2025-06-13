---
layout: publication
title: 'Merger-as-a-stealer: Stealing Targeted PII From Aligned Llms With Model Merging'
authors: Lin Lu, Zhigang Zuo, Ziji Sheng, Pan Zhou
conference: "Arxiv"
year: 2025
bibkey: lu2025merger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16094"}
tags: ['Security', 'Tools', 'Merging']
---
Model merging has emerged as a promising approach for updating large language
models (LLMs) by integrating multiple domain-specific models into a
cross-domain merged model. Despite its utility and plug-and-play nature,
unmonitored mergers can introduce significant security vulnerabilities, such as
backdoor attacks and model merging abuse. In this paper, we identify a novel
and more realistic attack surface where a malicious merger can extract targeted
personally identifiable information (PII) from an aligned model with model
merging. Specifically, we propose \texttt\{Merger-as-a-Stealer\}, a two-stage
framework to achieve this attack: First, the attacker fine-tunes a malicious
model to force it to respond to any PII-related queries. The attacker then
uploads this malicious model to the model merging conductor and obtains the
merged model. Second, the attacker inputs direct PII-related queries to the
merged model to extract targeted PII. Extensive experiments demonstrate that
\texttt\{Merger-as-a-Stealer\} successfully executes attacks against various LLMs
and model merging methods across diverse settings, highlighting the
effectiveness of the proposed framework. Given that this attack enables
character-level extraction for targeted PII without requiring any additional
knowledge from the attacker, we stress the necessity for improved model
alignment and more robust defense mechanisms to mitigate such threats.
