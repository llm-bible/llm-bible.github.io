---
layout: publication
title: 'The Fire Thief Is Also The Keeper: Balancing Usability And Privacy In Prompts'
authors: Zhili Shen, Zihang Xi, Ying He, Wei Tong, Jingyu Hua, Sheng Zhong
conference: "Arxiv"
year: 2024
bibkey: shen2024fire
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14318"}
tags: ['Prompting', 'Applications', 'Tools']
---
The rapid adoption of online chatbots represents a significant advancement in
artificial intelligence. However, this convenience brings considerable privacy
concerns, as prompts can inadvertently contain sensitive information exposed to
large language models (LLMs). Limited by high computational costs, reduced task
usability, and excessive system modifications, previous works based on local
deployment, embedding perturbation, and homomorphic encryption are inapplicable
to online prompt-based LLM applications.
  To address these issues, this paper introduces Prompt Privacy Sanitizer
(i.e., ProSan), an end-to-end prompt privacy protection framework that can
produce anonymized prompts with contextual privacy removed while maintaining
task usability and human readability. It can also be seamlessly integrated into
the online LLM service pipeline. To achieve high usability and dynamic
anonymity, ProSan flexibly adjusts its protection targets and strength based on
the importance of the words and the privacy leakage risk of the prompts.
Additionally, ProSan is capable of adapting to diverse computational resource
conditions, ensuring privacy protection even for mobile devices with limited
computing power. Our experiments demonstrate that ProSan effectively removes
private information across various tasks, including question answering, text
summarization, and code generation, with minimal reduction in task performance.
