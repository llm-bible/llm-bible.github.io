---
layout: publication
title: 'Effectiveness Of Zero-shot-cot In Japanese Prompts'
authors: Shusuke Takayama, Ian Frank
conference: "Arxiv"
year: 2025
bibkey: takayama2025effectiveness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.06765'}
tags: ['RAG', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
We compare the effectiveness of zero-shot Chain-of-Thought (CoT) prompting in
Japanese and English using ChatGPT-3.5 and 4o-mini. The technique of zero-shot
CoT, which involves appending a phrase such as "Let's think step by step" to a
prompt to encourage reasoning before answering, has been shown to offer LLM
performance improvements in mathematical and reasoning tasks, particularly in
English. We investigate how these effects transfer to Japanese using the
Japanese Multi-task Language Understanding Benchmark (JMMLU) and the Multi-task
Language Understanding Benchmark (MMLU). Our results show that while zero-shot
CoT prompting can lead to notable performance gains for some prompt categories
in GPT-3.5, its impact in GPT-4o-mini is associated with significant
performance declines. However, for Japanese prompts there remain certain
categories, such as college mathematics and abstract algebra, that still
exhibit improvements, despite the broader trend of diminishing effectiveness in
more advanced models.
