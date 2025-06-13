---
layout: publication
title: 'Chat-ts: Enhancing Multi-modal Reasoning Over Time-series And Natural Language Data'
authors: Paul Quinlan, Qingguo Li, Xiaodan Zhu
conference: "Arxiv"
year: 2025
bibkey: quinlan2025chat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10883"}
tags: ['Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models']
---
Time-series analysis is critical for a wide range of fields such as
healthcare, finance, transportation, and energy, among many others. The
practical applications often involve analyzing time-series data alongside
contextual information in the form of natural language to support informed
decisions. However, current time-series models are limited in their ability to
perform reasoning that involves both time-series and their textual content. In
this work, we address this gap by introducing \textit\{Chat-TS\}, a large
language model (LLM) based framework, designed to support reasoning over time
series and textual data. Unlike traditional models, Chat-TS integrates
time-series tokens into LLMs' vocabulary, enhancing its reasoning ability over
both modalities without compromising the core natural language capabilities,
enabling practical analysis and reasoning across modalities. To support
learning and evaluation in this setup, we contribute new datasets: the
\textit\{TS Instruct Training Dataset\} which pairs diverse time-series data with
relevant text instructions and responses for instruction tuning, the \textit\{TS
Instruct Question and Answer (QA) Gold Dataset\} which provides multiple-choice
questions designed to evaluate multimodal reasoning, and a \textit\{TS Instruct
Quantitative Probing Set\} which contains a small subset of the TS Instruct QA
tasks alongside math and decision-making questions for LLM evaluation. We
designed a training strategy to preserve the inherent reasoning capabilities of
LLMs while augmenting them for time-series reasoning. Experiments show that
Chat-TS achieves state-of-the-art performance in multi-modal reasoning tasks by
maintaining strong natural language proficiency while improving time-series
reasoning. ~\footnote\{To ensure replicability and facilitate future research,
all models, datasets, and code will be available at [\texttt\{Github-URL\}].\}
