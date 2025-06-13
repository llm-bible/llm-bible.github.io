---
layout: publication
title: 'Landermt: Detecting And Routing Language-aware Neurons For Selectively Finetuning Llms To Machine Translation'
authors: Shaolin Zhu, Leiyu Pan, Bo Li, Deyi Xiong
conference: "Arxiv"
year: 2024
bibkey: zhu2024detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19523"}
tags: ['Training Techniques', 'Applications', 'Tools']
---
Recent advancements in large language models (LLMs) have shown promising
results in multilingual translation even with limited bilingual supervision.
The major challenges are catastrophic forgetting and parameter interference for
finetuning LLMs when provided parallel training data. To address these
challenges, we propose LANDeRMT, a \textbf\{L\}anguage-\textbf\{A\}ware
\textbf\{N\}euron \textbf\{De\}tecting and \textbf\{R\}outing framework that
selectively finetunes LLMs to \textbf\{M\}achine \textbf\{T\}ranslation with
diverse translation training data. In LANDeRMT, we evaluate the awareness of
neurons to MT tasks and categorize them into language-general and
language-specific neurons. This categorization enables selective parameter
updates during finetuning, mitigating parameter interference and catastrophic
forgetting issues. For the detected neurons, we further propose a conditional
awareness-based routing mechanism to dynamically adjust language-general and
language-specific capacity within LLMs, guided by translation signals.
Experimental results demonstrate that the proposed LANDeRMT is very effective
in learning translation knowledge, significantly improving translation quality
over various strong baselines for multiple language pairs.
