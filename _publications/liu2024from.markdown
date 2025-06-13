---
layout: publication
title: 'From Solitary Directives To Interactive Encouragement! LLM Secure Code Generation By Natural Language Prompting'
authors: Shigang Liu, Bushra Sabir, Seung Ick Jang, Yuval Kansal, Yansong Gao, Kristen Moore, Alsharif Abuadbba, Surya Nepal
conference: "Arxiv"
year: 2024
bibkey: liu2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14321"}
tags: ['Security', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Fine-Tuning', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have shown remarkable potential in code
generation, making them increasingly important in the field. However, the
security issues of generated code have not been fully addressed, and the
usability of LLMs in code generation still requires further exploration.
  This work introduces SecCode, a framework that leverages an innovative
interactive encouragement prompting (EP) technique for secure code generation
with \textit\{only NL\} prompts. This approach ensures that the prompts can be
easily shared and understood by general users. SecCode functions through three
stages: 1) Code Generation using NL Prompts; 2) Code Vulnerability Detection
and Fixing, utilising our proposed encouragement prompting; 3) Vulnerability
Cross-Checking and Code Security Refinement. These stages are executed in
multiple interactive iterations to progressively enhance security. By using
both proprietary LLMs (i.e., GPT-3.5 Turbo, GPT-4 and GPT-4o) and open-source
LLMs (i.e., Llama 3.1 8B Instruct, DeepSeek Coder V2 Lite Instruct) evaluated
on three benchmark datasets, extensive experimental results show that our
proposed SecCode greatly outperforms compared baselines, generating secure code
with a high vulnerability correction rate. For example, SecCode exhibits a high
fix success rate of over 76% after running 5 automated EP interactive
iterations and over 89% after running 10 automated EP interactive iterations.
To the best of our knowledge, this work is the first to formulate secure code
generation with NL prompts only. We have open-sourced our code and encourage
the community to focus on secure code generation.
