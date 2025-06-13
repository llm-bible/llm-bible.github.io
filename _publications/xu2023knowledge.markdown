---
layout: publication
title: 'Knowledge-infused Prompting: Assessing And Advancing Clinical Text Data Generation With Large Language Models'
authors: Ran Xu, Hejie Cui, Yue Yu, Xuan Kan, Wenqi Shi, Yuchen Zhuang, Wei Jin, Joyce Ho, Carl Yang
conference: "ACL 2024"
year: 2023
bibkey: xu2023knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.00287'}
  - {name: "Code", url: 'https://github.com/ritaranx/ClinGen'}
tags: ['Has Code', 'Language Modeling', 'Applications', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
Clinical natural language processing requires methods that can address
domain-specific challenges, such as complex medical terminology and clinical
contexts. Recently, large language models (LLMs) have shown promise in this
domain. Yet, their direct deployment can lead to privacy issues and are
constrained by resources. To address this challenge, we delve into synthetic
clinical text generation using LLMs for clinical NLP tasks. We propose an
innovative, resource-efficient approach, ClinGen, which infuses knowledge into
the process. Our model involves clinical knowledge extraction and
context-informed LLM prompting. Both clinical topics and writing styles are
drawn from external domain-specific knowledge graphs and LLMs to guide data
generation. Our extensive empirical study across 7 clinical NLP tasks and 16
datasets reveals that ClinGen consistently enhances performance across various
tasks, effectively aligning the distribution of real datasets and significantly
enriching the diversity of generated training instances. Our code is available
at \url\{https://github.com/ritaranx/ClinGen\}.
