---
layout: publication
title: 'Green Prompting'
authors: Marta Adamska, Daria Smirnova, Hamid Nasiri, Zhengxin Yu, Peter Garraghan
conference: "Arxiv"
year: 2025
bibkey: adamska2025green
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.10666'}
tags: ['Language Modeling', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large Language Models (LLMs) have become widely used across various domains
spanning search engines, code generation, and text creation. However, a major
concern associated with their adoption is the high cost of inference, impacting
both their sustainability and financial feasibility. In this study, we
empirically study how different prompt and response characteristics directly
impact LLM inference energy cost. We conduct experiments leveraging three
open-source transformer-based LLMs across three task types\\(-\\)question
answering, sentiment analysis, and text generation. For each inference, we
analyzed prompt and response characteristics (length, semantic meaning, time
taken, energy consumption). Our results demonstrate that even when presented
with identical tasks, models generate responses with varying characteristics
and subsequently exhibit distinct energy consumption patterns. We found that
prompt length is less significant than the semantic meaning of the task itself.
In addition, we identified specific keywords associated with higher or lower
energy usage that vary between associated tasks. These findings highlight the
importance of prompt design in optimizing inference efficiency. We conclude
that the semantic meaning of prompts and certain task-related keywords
significantly impact inference costs, leading the way for deeper exploration
towards creating energy-adaptive LLMs.
