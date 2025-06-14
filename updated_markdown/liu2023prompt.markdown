---
layout: publication
title: 'Prompt Injection Attack Against Llm-integrated Applications'
authors: Yi Liu et al.
conference: "Arxiv"
year: 2023
citations: 38
bibkey: liu2023prompt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.05499'}
tags: ['RAG', 'Security', 'Applications', 'Fine-Tuning', 'Prompting']
---
Large Language Models (LLMs), renowned for their superior proficiency in
language comprehension and generation, stimulate a vibrant ecosystem of
applications around them. However, their extensive assimilation into various
services introduces significant security risks. This study deconstructs the
complexities and implications of prompt injection attacks on actual
LLM-integrated applications. Initially, we conduct an exploratory analysis on
ten commercial applications, highlighting the constraints of current attack
strategies in practice. Prompted by these limitations, we subsequently
formulate HouYi, a novel black-box prompt injection attack technique, which
draws inspiration from traditional web injection attacks. HouYi is
compartmentalized into three crucial elements: a seamlessly-incorporated
pre-constructed prompt, an injection prompt inducing context partition, and a
malicious payload designed to fulfill the attack objectives. Leveraging HouYi,
we unveil previously unknown and severe attack outcomes, such as unrestricted
arbitrary LLM usage and uncomplicated application prompt theft. We deploy HouYi
on 36 actual LLM-integrated applications and discern 31 applications
susceptible to prompt injection. 10 vendors have validated our discoveries,
including Notion, which has the potential to impact millions of users. Our
investigation illuminates both the possible risks of prompt injection attacks
and the possible tactics for mitigation.
